    pipeline {
    agent any

    tools {
        git 'Default Git' // Use the name given in the Git configuration
    }

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Dharmendra-Chourasiya/jenkin-cicd.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
                // Your build steps
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Your test steps
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Your deploy steps
            }
        }
    }

    post {
        always {
            echo 'This will always run'
        }
    }
}
    

   
  
