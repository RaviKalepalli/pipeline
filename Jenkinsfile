pipeline {
	agent any
	stages {
		stage('Start') {
			steps {
				echo 'Starting'
			}
		}
		
		stage('Permission') {
			steps {
				input('Do you want to proceed?')
			}
		}
		
		stage('Build') {
            steps {
              sh 'mvn clean install -DskipTests'
            }
        }
        
        stage('Test') {
            steps {
                bat 'Unit Test cases verification'
            }
        }
        
        stage('Check') {
            steps {
                bat 'Checking'
            }
        }      
		
	stage('Deploy') {
		steps {
			echo 'Deploy'
		}
		}		
	}
}
