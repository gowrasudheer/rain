pipeline {
agent any
stages {
stage('Clone-Repo') {
			steps {
				checkout scm
			}
}
stage('build') {
step {
sh 'mvn --version'
}
}
}
}
