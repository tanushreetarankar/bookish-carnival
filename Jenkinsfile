pipeline {
  agent any
  tools {
    maven 'Maven-3.9.3' 
  }
  stages {
    stage ('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}
