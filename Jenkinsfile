pipeline {
  agent any 
  tools {
    maven 'my_maven'
  }
  stages {
    stage('Compile & Build') {
      steps {
        sh "mvn compile"
      }
    }
    stage('Unit test') {
      steps {
        sh "mvn test"
      }
    }
  }
}
