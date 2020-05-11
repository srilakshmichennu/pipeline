pipeline {
  agent any
    
  tools {nodejs "nodejs"}
    
  stages {
        
    stage('Cloning Git') {
      steps {
        git 'https://github.com/satishchennu1/nodejspipeline.git'
      }
    }
        
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }
     
    stage('Test') {
      steps {
         sh 'npm test'
      }
    }      
  }
}




