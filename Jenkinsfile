pipeline {
    agent any

    stages {
        stage('Install Git') {
            steps {
                script {
                    // Install Git on the agent
                    sh 'sudo apt update -y'
                    sh 'sudo apt install git -y'
                    
                    // Verify Git installation
                    sh 'git --version'
                }
            }
        }

        // Add more stages for Build, Test, and Deploy as needed
        stage('Build') {
            steps {
                // Your build steps here
            }
        }

        stage('Test') {
            steps {
                // Your test steps here
            }
        }

        stage('Deploy') {
            steps {
                // Your deployment steps here
            }
        }
    }
}
