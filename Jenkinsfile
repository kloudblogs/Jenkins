pipeline {
    agent any

    stages {
        stage('Code Checkout') {
            steps {
                sh 'echo "Code checked out successfully"'
            }
        }

        stage('Code Build') {
            steps {
                sh 'echo "Code build successfully!"'
            }
        }
    }

    post {
        success {
            echo 'Pipeline execution completed successfully!'
        }
        failure {
            echo 'Pipeline execution failed!'
        }
    }
}
