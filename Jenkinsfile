pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
        sh 'pwd'
      }
    }
    stage('hello') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
