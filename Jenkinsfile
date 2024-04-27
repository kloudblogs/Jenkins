pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull code from Git repository
                git 'https://github.com/yourusername/yourrepository.git'
            }
        }

        stage('Print Message') {
            steps {
                // Print a message using a shell command
                sh 'echo "Code pulled successfully!"'
            }
        }
    }

    post {
        success {
            // Additional actions to perform on successful build
            echo 'Pipeline execution completed successfully!'
        }
        failure {
            // Additional actions to perform on failed build
            echo 'Pipeline execution failed!'
        }
    }
}
