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

        stage('Seccess Meesage_2') {
          steps {
            echo 'You Are Awesome!'
          }
        }

      }
    }

  }
}