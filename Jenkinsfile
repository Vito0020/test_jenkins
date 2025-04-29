pipeline {
    agent any
    
    environment {
        PYTHON_PATH = "C:\\Users\\vitna\\Python\\Python126\\python.exe"
    }
    
    stages {
        stage('version') {
            steps {
                bat "${PYTHON_PATH} --version"
            }
        }
        stage('hello') {
            steps {
                bat "${PYTHON_PATH} hello_world.py"
            }
        }
    }
}
