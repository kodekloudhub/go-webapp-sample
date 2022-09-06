pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh 'docker build -t adminturneddevops/go-webapp-sample ./...'
      }
    }

  }
}
