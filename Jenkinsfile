pipeline {
  agent {
    dockerfile true
  }
  stages {
    stage('Example') {
      steps {
        echo 'Hello World!'
        sh 'echo myCustomEnvVar = $myCustomEnvVar'
      }
    }
  }
}
