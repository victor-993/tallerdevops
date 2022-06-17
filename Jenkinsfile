pipeline {
    agent any
    tools {NodeJS "node"}
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('test') { 
            steps {
                sh 'npm run test' 
            }
        }
    }
}