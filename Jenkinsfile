pipeline {
	agent { label 'worker' }
	stages {
		stage('Pipeline Stages'){
			steps {
				sh "ls"
			}
		}
		stage(‘second stage’){
			steps {
				sh “pwd”
			}
		}
		stage(‘third stage’){
			steps {
				sh “touch file.txt”
			}
		}
		stage(‘fourth stage’){
			steps {
				sh “mv file.txt file1.txt”
			}
		}
	}
}
