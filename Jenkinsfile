pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                echo 'compiling...'
                sh 'mvn compile' // Example Maven command
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'mvn test' // Example Maven command
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'mvn package' // Example Maven command
            }
        }
    }
}
