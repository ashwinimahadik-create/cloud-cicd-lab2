pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Starting Cloud CI/CD Pipeline'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Flask Application'
            }
        }

        stage('Docker Build') {
            steps {
                sh 'docker --version'
            }
        }
    }
}
