//DECLARATIVE

pipeline {
	agent any
	//agent { docker { image 'maven:3.6.3'} }
	stages {
		stage('Build') {
			steps {
				//sh 'mvn version'
				echo "Build"
				echo "$PATH"
				echo "BUILD NUMBER - $env.BUILD_NUMBER"
				echo "$env.BUILD_ID"
				echo "$env.JOB_Name"
			}		
		}		
		stage('Test') {
			steps {
				echo "Test"
			}		
		}
		stage('Integration Test') {
			steps {
				echo "Integration test"
			}		
		}		
	}

}
