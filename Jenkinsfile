pipeline {
    agent {label 'ubuntu'}
    stages {
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
        stage('test') {
            steps {
                sh 'npm config ls'
            }
        }
        stage('deploy') {
            steps {
                sh 'node server.js' 
            }
        }
    }
}
