pipeline {
	agent {
		docker {
			image 'node:16-alpine'
			args '-u root'
			alwaysPull false
			reuseNode true
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

