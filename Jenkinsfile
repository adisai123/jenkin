pipeline {
  agent none
  stages {
    stage('print') {
      parallel {
        stage('print') {
          steps {
            echo 'hi ${aditya}'
          }
        }

        stage('error') {
          steps {
            echo 'hiii'
          }
        }

      }
    }

  }
  environment {
    aditya = 'a'
  }
}