pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        archiveArtifacts(artifacts: 'target/*.jar', fingerprint: true)
        sh 'echo You should not see me!'
      }
    }
  }
}