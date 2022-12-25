pipeline {
  agent {
    docker{
      image 'python:2-alpine'
      }
    }
  stages {
    stage('version') {
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
