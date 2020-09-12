pipeline {
  agent {
    docker {
      image 'node:14-alpine '
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Verify') {
      agent any
      environment {
        name = 'CERT'
      }
      steps {
        echo 'Job is triggered!'
      }
    }

  }
}