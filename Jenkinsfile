pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checked out successfully'
            }
        }

        stage('Demo Steps') {
            steps {
                sh 'echo "Hello from Jenkins!"'
                sh 'date'
                sh 'whoami'
                sh 'pwd'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully 🎉'
        }
        always {
            echo 'Pipeline finished'
        }
    }
}
