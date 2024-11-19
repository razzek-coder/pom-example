pipeline {
	agent any
	tools {
		maven 'maven 3.9.9'
	}

	stages {
		stage('Package') {
			steps {
				bat 'mvn -B -q clean package'
			}
		}
  }
}
