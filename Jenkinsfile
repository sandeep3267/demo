pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello, World!'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Simulate a build step, e.g., compile code or build a Docker image
                sh 'echo "This is a simulated build step"'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Simulate a test step
                sh 'echo "Tests are running"'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Simulate a deployment step
                sh 'echo "Application deployed"'
            }
        }
    }
    
    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed. Check the logs for details.'
        }
    }
}
