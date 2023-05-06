/*pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}*/


pipeline {
    
  environment {
    dockerimagename = "bravinwasike/react-app"
    dockerImage = ""
  }
    
  agent any
    
  stages {  
    stage('Checkout Source') {
      steps {
        git 'https://github.com/Bravinsimiyu/jenkins-kubernetes-deployment.git'
      }
    }
}






