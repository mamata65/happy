pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'echo "This is Mamata and welcome to testing"'
      }
    }

    stage('Dev') {
      steps {
        echo 'This is my development ENV'
      }
    }

    stage('Prod') {
      steps {
        echo 'Inside production environment'
      }
    }

  }
}