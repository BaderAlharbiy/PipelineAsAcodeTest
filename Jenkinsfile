pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Compeleted'
        timeout(time: 5, unit: 'SECONDS') {
         sh 'sleep 10'
          }
      }
    }
    stage('Testing') {
      steps {
        echo 'Tesying Compeleted'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy Compeleted'
      }
    }

  }
}