pipeline {
<<<<<<< HEAD
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
=======
  agent any
  stages {
    stage('Pre-Build') {
      steps {
        echo 'Release in Dev Envireontment'
      }
    }

  }
}
>>>>>>> 5e4c7f2cc43ce40595b3697a236acf80b37d0f76
