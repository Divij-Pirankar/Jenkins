pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing...'
                bat 'python --version'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
        
        stage('Hello World') {
            steps {
                echo 'Running Hello World Python script...'
                bat 'python -c "print(\'Hello, World!\')"'
            }
        }
    }
}
