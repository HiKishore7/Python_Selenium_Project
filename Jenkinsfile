pipeline {
    agent any
    stages {
        stage('Install') {
            steps {
                bat 'pip install selenium pytest'
            }
        }
        stage('Test') {
            steps {
                bat 'pytest'
            }
        }
    }
}