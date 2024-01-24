pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sudo apt install git -y 
                git clone https://github.com/mohan-chandra2626/practice_CIS.git
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
