pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                // This step will be for building the Docker image
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                // In here I need to run the pytest for the application once the container is running
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Push Image') {
            steps {
                echo 'Pushing image to repository....'
            }
        }
    }
}