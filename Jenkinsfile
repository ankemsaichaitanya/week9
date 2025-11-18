pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo "Checking out source code..."
            }
        }

        stage('Build') {
            steps {
                bat 'docker build -t week9 .'
            }
        }

        stage('Test') {
            steps {
                echo "Running test script..."
                bat 'echo No tests configured'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying container..."
                bat 'docker run -d -p 3000:3000 week9'
            }
        }
    }
}
