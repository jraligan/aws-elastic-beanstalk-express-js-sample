pipeline {
    agent {
        docker {
            image 'node:16-alpine' 
            args '-u root' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install --save' 
            }
        }
    }
}
