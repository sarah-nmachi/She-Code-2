pipeline {
   
    agent any
     tools {nodejs "nodejs"}
    stages {
       stage('Cloning Git') {
      steps {
        git 'https://github.com/sarah-nmachi/She-Code-2.git'
      }
    }
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
      stage('Test') {
            steps {
                sh './test.sh'
            }
        }
         
    }
}
