pipeline {
    agent any
    tools {nodejs "node-js-app"}

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
