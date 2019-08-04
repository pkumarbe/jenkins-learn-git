pipeline {
    agent {
        docker { image 'python:2.7-slim' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}