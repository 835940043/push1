pipeline{
	agent any
		stages{
			stage('build-stage') {
				steps {
					echo 'Hi ...This is my first jenkins pipeline job and running from build stage...pls run successfully'
					}
				}

			
			stage('Test-stage') {
				steps {
					input('Do you wish to continue (Y/N):')
					}
				}
			stage('deploy') {
				steps {
				
					echo 'Just deploying the build ...Good Bye'				
					
					}

				}
 
			}
	}
