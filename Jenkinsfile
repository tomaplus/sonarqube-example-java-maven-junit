pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'mvn install'
        echo 'Done'
      }
    }
    stage('Test') {
      steps {
        sh 'mvn test'
      }
    }
  }
}