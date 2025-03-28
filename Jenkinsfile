pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the code...'
                sh 'g++ program.cpp -o PES1UG22CS543-1'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh './PES1UG22CS543-123'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }

    post {
        failure {
            echo 'Pipeline failed'
        }
    }
}
