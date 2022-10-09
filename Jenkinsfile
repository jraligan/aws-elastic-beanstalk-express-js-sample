pipeline {
    agent {
        docker {
            image 'node:16-alpine' 
            args '-u admin' 
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
