pipeline {
  agent any
  stages {
    stage('Example') {
      steps {
        echo 'Hello World!'
      }
    }
    stage('Example2') {
      steps {
        input 'waiting'
      }
    }
    stage('Example3') {
      steps {
        sh 'sleep 60'
      }
    }
  }
}