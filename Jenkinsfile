pipeline {
  agent any
  stages {
    stage('Connect to DSM') {
      steps {
        sh '''pwd > pwd.txt
cat pwd.txt
'''
      }
    }

    stage('Shell Script 1') {
      steps {
        sh '''ls > artahmed.txt
'''
        archiveArtifacts(artifacts: '/var/lib/jenkins/workspace/Jenkins_Developmen-branch/*.txt', fingerprint: true)
      }
    }

  }
}