pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python -m --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python -m runTest.py'
      }
    }
  }
}
