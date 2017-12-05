pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build'
      }
    }
    stage('Test') {
      parallel {
        stage('Linux') {
          steps {
            echo 'Test'
          }
        }
        stage('MacOS') {
          steps {
            echo 'Test'
          }
        }
        stage('Windows') {
          steps {
            echo 'Test'
          }
        }
      }
    }
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