pipeline {
    agent any
    stages {
        stage ('Build') {
	    steps {
	        sh 'echo "Build Completed."'
	    }
	}
	stage('Command Execution') {
	    steps {
	        sh 'ls -ld'
		sh 'w > text.txt'
		sh 'fdisk -h'
		sh 'echo "All Commands Executed Successfully!"'
	    }
        }
    }
}

