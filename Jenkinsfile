pipeline {
	agent any

	stages {
		stage ('Build') {
			steps {
				sh "mvn clean package -DskipTests"
			}
		}
		
		stage ('Test') {
			steps {
				sh "mvn test"
			}
		}
	}
}
