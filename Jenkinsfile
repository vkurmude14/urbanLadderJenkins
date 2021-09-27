pipeline{
	agent any
	tools{
	maven 'MAVEN_HOME'
	}
	stages{
		stage('checkout'){
			steps{
				git 'https://github.com/vkurmude14/HybridUrbanLadder.git'
			}
		}
		stage('mvn Test'){
			steps{
				bat 'mvn --version'
			}
		}
		stage('Build'){
			steps{
				bat 'mvn clean install'
			}
		}

		
	}
}
