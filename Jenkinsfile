
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'echo "Building Quiet Hours website"'
            }
        }

        stage('Test') {
            steps {
                bat 'if not exist index.html exit /b 1'
                bat 'echo "HTML file verified successfully"'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo "Quiet Hours website is ready!"'
            }
        }

        stage('End') {
            steps {
                bat 'echo "Pipeline completed successfully"'
            }
        }
    }
}
