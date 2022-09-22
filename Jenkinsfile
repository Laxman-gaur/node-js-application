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
                sh './script/test'
            }
        }
        stage('Deploy') {
            steps {
                sh './script/deploy'
            }
        }
    }
}
