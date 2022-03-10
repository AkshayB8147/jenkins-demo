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
            sh "mvn clean compile"
            }
        }
        
         stage("package"){
            steps{
            sh "mvn package"
            }
        }
       
        }
    }
    }
   
}
