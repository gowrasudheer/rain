pipeline {
	agent any 
	stages {
	    stage('build') {
		steps {
			sh 'git -version'
			sh '''
			    echo "multiline shell"
			    ls -lah 
			'''
			}
		}
	}
}
