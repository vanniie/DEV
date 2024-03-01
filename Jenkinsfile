pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Clone the repository
                git 'https://github.com/vanniie/DEV.git'
            }
        }
        
        stage('Build') {
            steps {
                // Build your project
                sh 'mvn clean package'
            }
        }
        
        stage('Test') {
            steps {
                // Run tests
                sh 'mvn test'
            }
        }
        
        stage('Deploy') {
            steps {
                // Deploy your application
                sh 'mvn deploy'
            }
        }
    }
}
