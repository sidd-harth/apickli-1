pipeline {
  agent any
    tools {
        maven 'M2'
        jdk 'JDK'
        nodejs 'NODEJS'
    }
    stages {
        stage ('pwd1') {
            steps {
                bat "pwd"
            }
        }
stage ('pwd2') {
            steps {
              bat "cd source && npm install"
      
               bat "cd source && gulp test"
            }
        }
       
    }
        
    
}
