pipeline {
  agent none
   environment {
    CI = 'true'
  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "sureshbabu jagat sffsfha"'
      }
    }
    stage('Test') {
      steps {
        sh './jenkins/scripts/test.sh'
      }
    }
  }
}
