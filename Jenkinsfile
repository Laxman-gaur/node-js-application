pipeline {
    agent any
    stages {
        stage('git-clone ') {
            steps {
                sh 'git clone https://github.com/Laxman-gaur/node-js-application.git' 
            }
        }
        stage('change directory') {
            steps {
                sh 'cd /home/ubuntu/node/node-js-application' 
            }
        }
        stage('build') {
            steps {
                sh 'npm install'
                sh 'npm audit fix --force'
                sh 'npm install'
            }
        }
        stage('deploy') {
            steps {
                sh 'node server.js' 
            }
        }
    }
}
