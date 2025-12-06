pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
        git branch: 'main', url: 'https://github.com/Saquib71/Saquib-TechnoHacks-Task2.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deployment step..."
            }
        }
    }
}
