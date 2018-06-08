pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell(script: 'write-host "hellow"', returnStatus: true, returnStdout: true)
      }
    }
    stage('Deploy') {
      steps {
        echo 'hellow'
      }
    }
  }
  environment {
    serviceId = 'user'
  }
}