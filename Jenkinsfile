pipeline{
	agent any
	tools{
		maven 'maven3.9'
	}
	stages{
		stage("Checkout Code"){
		steps{
			git branch: 'master' , url: 'https://github.com/chinmay1998/Java_Project.git'
		     }
		}	 
		stage("Build_Code"){
		steps{
			sh 'mvn clean package'
		     }
		}
	
	}
}