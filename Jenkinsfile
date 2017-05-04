pipeline {
  agent any
  stages {
    stage('Unit') {
      steps {
        sh '''npm install -g dredd
dredd
'''
      }
    }
  }
}