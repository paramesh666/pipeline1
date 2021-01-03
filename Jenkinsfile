pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/mitreid-connect/simple-web-app.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn install'
            }
        }
        stage('test') {
            steps {
                echo 'Testing the application'
            }
        }
        stage('deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
