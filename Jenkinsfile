pipeline{
    agent any
    stages{
        stage("clone"){
            steps{
                git "https://github.com/AkshayB8147/jenkins-demo.git"
            }
        }
        stage("compile"){
            steps{
            bat "mvn clean compile"
            }
        }
        
         stage("package"){
            steps{
            bat "mvn package"
            }
        }
       
	}
}
