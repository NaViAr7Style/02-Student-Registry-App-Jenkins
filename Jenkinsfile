pipeline {
    agent any

    stages {
        stage('Install Node modules') {
            steps {
                bat 'npm install'
            }
        }

        stage('Run Audit Tests') {
            steps {
                bat 'npm audit'
            }
        }

        stage('Run Integration Tests') {
            steps {
                bat 'npm test'
            }
        }
    }
}
