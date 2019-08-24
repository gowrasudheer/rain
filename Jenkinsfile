pipeline {
	agent any 
	stages {
	    stage('build') {
		steps {
			sh 'echo "he"'
			sh '''
			    echo "multiline shell"
			    ls -lah 
			'''
			}
		}
	}
}
