pipeline {
	agent any 
	stages {
	    stage('build') {
		steps {
<<<<<<< HEAD
			sh 'git -version'
=======
			sh 'mvn --version'
>>>>>>> 9fac157268402bced989d6db648c07783caadb86
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
