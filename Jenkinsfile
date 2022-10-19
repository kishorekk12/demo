pipeline {
  agent none
  stages {
    stage('code checkout') {
      steps {
        git 'https://github.com/kishorekk12/demo.git'
      }
    }

    stage('compile') {
      steps {
        bat 'mvn install'
      }
    }

  }
  environment {
    ENV = 'hello'
  }
}