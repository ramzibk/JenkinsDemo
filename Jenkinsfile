pipeline {
	agent any

	stages {
		stage ('Build') {
			steps {
				sh "mvn spring-boot:build"
			}
		}
		
		stage ('tEST') {
			steps {
				sh "mvn spring-boot:test"
			}
		}
	}
}
