pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                bat 'echo "Executando o comando Docker Build"'
            }
        }

        stage('Push Docker Image') {
            steps {
                bat 'echo "Executando o comando Docker Push"'
            }
        }

        stage('Deploy no Kubernetes') {
            steps {
                bat 'echo "Executando o comando kuberctl apply"'
            }
        }
    }
}