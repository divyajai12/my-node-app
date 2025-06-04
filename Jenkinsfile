pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main' url 'https://github.com/divyajai12/my-node-app.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo Building the application...'
            }
        }
        stage('Test') {
            steps {
                sh 'echo Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploying application...'
            }
        }
    }
}
