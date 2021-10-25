//Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any

    stages {
        stage('Clone') {
            steps{
            git 'https://github.com/StCryox/jenkins_test.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}