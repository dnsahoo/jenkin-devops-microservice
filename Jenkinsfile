//SCRIPTED

//DECLARATIVE
pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo 'Build'
			}
		}
		stage('Test') {
			steps {
				echo 'Test'
			}
		}
		stage('Integration Test') {
			steps {
				echo 'Integration Test'
			}
		}
	} 
	post {
		always {
			echo 'I am awesome. I run always'
		}
		success {
			echo 'I am when u success'
		}
		failure {
			echo 'I am when u failure'
		}
	}
	
}
