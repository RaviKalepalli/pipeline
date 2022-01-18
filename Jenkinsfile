pipeline {
	agent any
	stages {
		stage('Start') {
			steps {
				echo 'Starting Pipeline Project'
			}
		}
		
		stage('Check') {
			steps {
				input('Do you want to proceed?')
			}
		}
		
		stage('Build') {
            steps {
                echo 'Build with Maven'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Test my unit test cases'
            }
        }
        
        stage('Check') {
            steps {
                echo 'Verification '
            }
        }      
		
	stage('Depoy') {
		steps {
			echo 'Deployment'
		}
		}		
	}
	

}
