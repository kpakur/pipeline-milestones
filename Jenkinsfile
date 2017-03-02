#!groovy

// testing milestones behaviour

stage('hello'){
	echo 'hello, checking milestones behaviour, will just one step box be red or all red'
}

milestone 1

stage('will old fail'){
	input message: 'will old fail all red or jus one step red?'
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