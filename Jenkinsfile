pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/janasakthi05/Feedback-Collection-and-Basic-Analysis.git'
            }
        }

        stage('Install') {
            steps {
                sh 'npm install'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Build successful'
            }
        }
    }
}
