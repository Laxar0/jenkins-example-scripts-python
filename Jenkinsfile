pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        bat 'python3 hello.py'
      }
    }
    stage('main') {
      steps {
        bat 'python3 main.py'
      }
    }
    stage('test_os') {
      steps {
        bat 'python3 test_os.py'
      }
    }
  }
}
