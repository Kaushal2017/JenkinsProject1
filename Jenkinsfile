pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell(script: 'write-host "hellow"', returnStatus: true, returnStdout: true)
      }
    }
  }
  environment {
    serviceId = 'user'
  }
}