pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // You can replace this with your build command
                sh 'echo "Building..."'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Replace this with your test command
                sh 'echo "Running tests..."'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Replace with your deployment command
                sh 'echo "Deploying..."'
            }
        }
    }

    post {
        always {
            echo 'Cleaning up...'
            // Add any cleanup steps if needed
        }
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
