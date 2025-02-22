pipeline {
    agent any

    stages {
        stage('Install Node modules') {
            steps {
                bat 'npm install'
            }
        }

        stage('Run Integration Tests') {
            steps {
                bat 'npm test'
            }
        }
    }
}
