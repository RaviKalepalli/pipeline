pipeline {
	agent any
	environment {
      PATH = "D:\apache-maven-3.6.3:$PATH"
		
 		 }
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
		echo 'Ravi121212'
            	sh 'pwd'
		   
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
