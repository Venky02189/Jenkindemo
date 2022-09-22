pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
              
                    sh 'echo Compile is successful'
                    sh 'ls'
                    emailext body: 'Status of project', recipientProviders: [developers()], subject: 'Status of project', to: 'Sunilteja206@gmail.com'  
                }
            }

        stage ('Testing Stage') {

            steps {
                 
                    sh 'echo Testing is done'
                }
            }

        stage ('Deployment Stage') {
            steps {
                  sh 'echo Deployement is done'
            }
                }
            }
        }
