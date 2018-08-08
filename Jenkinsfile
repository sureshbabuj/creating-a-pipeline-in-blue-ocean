pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        sh 'echo "sureshbabu"'
      }
    }
    stage('Test') {
      steps {
        sh './jenkins/scripts/test.sh'
      }
    }
  }
  environment {
    CI = 'true'
  }
}