pipeline {
	agent any
	tools {
		maven 'maven 3.9.9'
	}

	stages {
		stage('Compilacion') {
			steps {
				bat 'mvn -pl war-example-updated clean compile'
			}
		}
		stage('Package') {
			steps {
				bat 'mvn package'
			}
		}
	}
}
