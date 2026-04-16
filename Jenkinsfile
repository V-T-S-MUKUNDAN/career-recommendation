pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/V-T-S-MUKUNDAN/career-recommendation.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building project...'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deploying...'
            }
        }
    }
}