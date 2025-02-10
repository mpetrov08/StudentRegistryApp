pipeline {
    agent any
    stages {
        stage('Npm Install') {
            steps {
                bat 'npm install'
            }
        }
        stage('Run Tests') {
            steps {
                bat 'npm run test'
            }
        }
    }
}