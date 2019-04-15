pipeline {
  agent any
  stages {
    stage('hello') {
      steps {
        echo 'Hello,$MESSAGE!'
      }
    }
  }
  environment {
    MESSAGE = 'World'
  }
}