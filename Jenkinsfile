pipeline {
  agent none
   environment {
    CI = 'false'
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
