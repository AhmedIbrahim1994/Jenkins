pipeline {
  agent any
  stages {
    stage('Connect to DSM') {
      steps {
        sh 'pwd'
      }
    }

    stage('Shell Script 1') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}