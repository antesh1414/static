pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				sh 'echo "Hello World with AWS"'
				sh '''
					echo "Multiline shell steps work too"
				'''
				ls -lah
			}
		}
	}
}
