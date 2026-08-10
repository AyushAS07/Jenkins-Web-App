pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out project from GitHub...'
            }
        }

        stage('Build') {
            steps {
                echo 'Build step started...'
                bat 'dir'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing web application...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying web application...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }

        failure {
            echo 'Pipeline failed!'
        }
    }
}