pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd result
npm install
npm ls'''
      }
    }

  }
}