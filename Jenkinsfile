pipeline {
    label node-1

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
        
        stage('deploy') {
            steps {
                sh 'npm deploy'
            }
        }
    }
}
