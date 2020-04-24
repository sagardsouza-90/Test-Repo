@Library(Jenkins-Library@master) _
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Hello World"
                sh """
		           pwd
		           ls -lart
	              """
            }
        }
    }
}