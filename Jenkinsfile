pipeline {
  agent any
 
  tools {nodejs "NodeJS"}
 
  stages {
        
    stage('Cloning Git') {
      steps {
        git 'https://github.com/ashishjain16/simple-node-js-react-npm-app'
      }
    }
        
    stage('Install dependencies') {
      steps {
        bat 'npm install'
      }
    }
     
    stage('Test') {
      steps {
         bat 'npm config ls'
      }
    }      
  }
}