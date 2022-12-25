pipeline {
  agent none
  stages {
    stage('version') {
      agent {
        docker {
          image 'python:2-alpine'
        }
      }
      steps {
        sh 'python --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python runTest.py'
      }
    }
  }
}
