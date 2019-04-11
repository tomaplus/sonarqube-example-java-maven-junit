pipeline {
  agent {
    docker {
      image 'alpine'
    }

  }
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo Hello'
            sh 'docker build '
          }
        }
        stage('') {
          steps {
            sh 'sonnarScaner'
          }
        }
      }
    }
  }
}