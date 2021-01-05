//DECLARATIVE

pipeline {
	// agent any
	agent { docker {image 'Maven:3.6.3'} }
		stages { 
			Stage('Build') {
				steps {
					sh "mvn --version"
					echo "Build"
			}
		}
	}	
	stage('Test') {
		echo "Test"
	}
	
	stage('Integration Test') {
		echo "Integration Test"
	}
}
