pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo "Repository cloned successfully"
            }
        }

        stage('Build Docker Image') {
            steps {
                bat 'docker build -t week9 .'
            }
        }

        stage('Run Container') {
            steps {
                bat 'docker run -d -p 3000:3000 week9'
            }
        }
    }
}
