pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat "C:\\Users\\vitna\\Python\\Python126\\python.exe --version"
        }
    }
    stage('hello') {
      steps {
        bat 'python hello_world.py'
      }
    }
  }
}
