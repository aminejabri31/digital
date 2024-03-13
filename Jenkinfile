pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
              git credentialsId: 'GitHub', url: 'https://github.com/aminejabri31/digital.git'
               }
        }
    }
}
