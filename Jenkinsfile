pipeline {
  agent any
  stages {
    stage('Connect to DSM') {
      steps {
        sh 'pwd > pwd'
      }
    }

    stage('Shell Script 1') {
      steps {
        sh '''ls > artahmed.txt
'''
        archiveArtifacts(artifacts: 'target/*.txt', fingerprint: true)
      }
    }

  }
}