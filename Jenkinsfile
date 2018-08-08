pipeline {
  agent none
   environment {
    CI = 'true'
  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "ssffssdfsdfgdsgffha"'
      }
    }
    stage('Test') {
      steps {
        sh './jenkins/scripts/test.sh'
      }
    }
  }
}
