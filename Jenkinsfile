pipeline{
	agent any
	stages {
		stage('Permisson'){
			steps{
				sh "chmod 777 mvnw"
			}
		}
		stage("Compile"){
			steps{
				sh "./mvnw compile"
			}
		}
		stage("Unit Test"){
			steps{
				sh "./mvnw test"
			}
		}
	}
}