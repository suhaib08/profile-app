pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Test') {
            steps {
                bat 'echo Jenkins successfully pulled profile-app'
                bat 'git --version'
                bat 'docker version'
                bat 'kubectl get nodes'
            }
        }
    }
}