pipeline {
	agent any 
	stages {
	    stage('build') {
		steps {
			sh 'mvn --version'
			sh '''
			    echo "multiline shell"
			    ls -lah 
			'''
			stage('email')
			stpes {
			emailext body: '', subject: 'compiile', to: 'yarapakalyan@gmail.com'
				}
			}
		}
	}
}
