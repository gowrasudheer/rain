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
			
			}
		}
	
	}
	post {
		always {
			emailext body: '', subject: 'compiile', to: 'yarapakalyan@gmail.com'
		}
	}
}
