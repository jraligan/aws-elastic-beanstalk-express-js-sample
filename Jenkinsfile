pipeline {
	agent {
		docker {
			image 'node:16.15.1-alpine'
			args '-u root -p 2375'
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

