/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }
    stages {
        stage('bonjour') {
            steps {
                sh 'Hello world'
            }
        }
        stage('build') {
            steps {
                sh '''
                     python --version
                '''
            }
        }
    }
}
