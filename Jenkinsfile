pipeline {
	agent {
		docker {
			image 'node:16-alpine'
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

