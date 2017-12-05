pipeline {
  agent any
  stages {
    stage('Deploy release') {
      when {
        branch 'master'
      }
      steps {
        echo 'Deploy to production'
      }
    }
  }
}