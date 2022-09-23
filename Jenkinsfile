pipeline {
    agent node-1
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
                sh 'npm config ls' 
            }
        }
    }
}
