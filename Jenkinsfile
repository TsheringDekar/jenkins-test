pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // This automatically checks out the code from the same repo where Jenkinsfile is located
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Running build stage...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running test stage...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
