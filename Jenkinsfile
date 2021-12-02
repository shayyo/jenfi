pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bash 'docker-compose up'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
