pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                sh 'Deploying'
            }
        }
    }
}
