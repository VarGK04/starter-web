pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'git --version'
            }
        }
        stage('Test') {
            steps {
                sh 'jenkins --version'
            }
        }
        stage('Deploy') {
            steps {
                sh 'java -version'
                sh 'git pull origin master'
            }
        }
    }
}
