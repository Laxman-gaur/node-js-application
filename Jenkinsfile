pipeline {
    agent {
        label 'node-1'

        stages {
        stage('Build') { 
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
