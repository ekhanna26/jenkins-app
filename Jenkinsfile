pipeline {
    agent any
    
    stages {
        stage ('Clean workspace') {
          steps {
            cleanWs()
          }
        }
        stage ('Git Checkout') {
          steps {
              git branch: 'master', credentialsId: '1', url: 'https://github.com/ekhanna26/jenkins-app.git'
            }
          }
        stage('Echo Workspace') {
          steps {
            bat echo "${workspace}"
          }
        }
         stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
