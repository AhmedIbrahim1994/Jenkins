pipeline {
  agent any
  stages {
    stage('Connect to DSM') {
      steps {
        sh 'pwd'
      }
    }

    stage('Success Message') {
      parallel {
        stage('Success Message') {
          steps {
            echo 'Well Done!'
          }
        }

        stage('') {
          steps {
            echo 'You Are Awesome!'
          }
        }

      }
    }

  }
}