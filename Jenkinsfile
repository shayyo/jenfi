pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                docker-compose up
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
