pipeline {
	agent any

	stages {
		stage ('Build') {
			steps {
				sh "mvn spring-boot:install -DskipTests"
			}
		}
		
		stage ('Test') {
			steps {
				sh "mvn spring-boot:test"
			}
		}
	}
}
