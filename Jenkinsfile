pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building"
            }
        }
        stage('Test') {
            steps {
                echo "Testing"
            }
        }
        stage('Staging') {
            steps {
                echo "Staging"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy"
            }
        }
        stage('Monitor') {
            steps {
                echo "Monitor"
            }
        }
        stage('Execute python code') {
            steps {
                sh "python3 hello.py"
                sh "python3 hello.py"
            }
        }
    }
}