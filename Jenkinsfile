/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }
    stages {
        stage('checkout') {
            steps {
                echo 'Hello World'
            }
        }
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('test') {
            steps {
                sh 'python --version'
            }
        }
        state('deploy') {
            steps {
                sh 'python --version'
            }
        }
    }
}