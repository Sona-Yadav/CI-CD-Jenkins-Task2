pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'docker build -t simple-jenkins-app .'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the application...'
                // Add test steps if needed
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                sh 'docker run --rm simple-jenkins-app'
            }
        }
    }
}
