pipeline {
  agent none
  stages {
    stage('build') {
      steps {
        sh '''cd results
npm install
npm ls'''
      }
    }

  }
}