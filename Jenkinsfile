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
		sh 'fdisk -l > text.txt'
		sh 'df -h > text.txt'
		sh 'echo "All Commands Executed Successfully!"'
	    }
        }
    }
}

