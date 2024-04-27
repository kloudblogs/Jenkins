pipeline {
    agent any

    stages {
        stage('Code Cheeckout') {
            steps {
                sh 'echo "code checked out successfully"
            }
        }

        stage('Code Build') {
            steps {
                sh 'echo "Code Build successfully!"'
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
