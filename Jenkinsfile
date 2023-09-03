pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the repository
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Your build commands go here
                sh 'echo "Build steps go here"'
            }
        }
        // Add more stages as needed
    }
}



