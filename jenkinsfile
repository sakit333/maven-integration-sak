pipeline {
  agent any 
    tools { 
      maven 'maven'
    }
    stages {
      stage('compile') {
        steps {
         sh "mvn compile" //sh-shell,windows bat
        }
      }
      stage('test') {
        steps {
         sh "mvn test" 
      }
    }
  }
}
