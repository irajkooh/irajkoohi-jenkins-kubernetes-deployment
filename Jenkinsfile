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
    dockerimagename = "irajkoohi/react-app"
    dockerImage = ""
  }
    
  agent any
    
  stages {  
    stage('Checkout Source') {
      steps {
        // git 'https://github.com/Bravinsimiyu/jenkins-kubernetes-deployment.git'
        git 'https://github.com/irajkooh/jenkins-kubernetes-deployment.git  '
      }
    }
}
    






