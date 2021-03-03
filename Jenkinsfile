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
        sh '''ls > artahmed.txt
'''
        archiveArtifacts(artifacts: './*.txt', fingerprint: true)
      }
    }

  }
}