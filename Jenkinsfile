pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                script {
                    // Build your Docker image
                    bat 'docker build -t my-kube3-chinna .'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Run tests here if you have any
                    echo 'Running tests...'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    // Deploy your Docker image
                    echo 'Deploying application...'
                }
            }
        }
    }
}pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                script {
                    // Build your Docker image
                    bat 'docker build -t my-kube3-chinna .'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Run tests here if you have any
                    echo 'Running tests...'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    // Deploy your Docker image
                    echo 'Deploying application...'
                }
            }
        }
    }
}
