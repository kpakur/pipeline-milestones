#!groovy

// testing milestones behaviour

stage('hello'){
	echo 'hello, checking milestones behaviour, will just one step box be red or all red'
}

milestone 1

stage('will old fail'){
	input message: 'will old fail all red or jus one step red?'
}

stage('sleep 30 seconds'){
	sleep(time:30,unit:"SECONDS")
}

stage('sleep 60 seconds'){
	sleep(time:60,unit:"SECONDS")
}

milestone 2

stage('will old fail'){
	input message: 'will old fail all red or jus one step red?'
}

milestone 3

stage('will old fail'){
	input message: 'will old fail all red or jus one step red?'
}

milestone 4

stage('will old fail in node'){
	input message: 'will old fail all red or jus one step red?'
}

stage('in node'){
	node{
		milestone 5
	}
}
stage('will old fail in node'){
	input message: 'will old fail all red or jus one step red?'
}

stage('in node'){
	node{
		if (BUILD_NUMBER % 2 == 0) {
			error("fail here")
		}
		milestone 6
	}
}

stage('will old fail in node'){
	input message: 'will old fail all red or jus one step red?'
}

stage('in node'){
	node{
		milestone 7
	}
}

stage('will old fail in node'){
	input message: 'will old fail all red or jus one step red?'
}

stage('in node'){
	node{
		milestone 8
	}
}

stage('sleep 600 seconds'){
	sleep(time:600,unit:"SECONDS")
}
