pipeline {
    agent any

    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
    stages {
        stage('test') { 
            steps {
                sh 'testing' 
            }
        }
    }
}
