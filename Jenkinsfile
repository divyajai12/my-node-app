pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/yourusername/yourrepo.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the application..."'
                // Add your build commands here
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
                // Add test commands here
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying application..."'
                // Add deployment commands here
            }
        }
    }
}
