pipeline {
  agent {
    node {
      label '123'
    }

  }
  stages {
    stage('wait') {
      parallel {
        stage('wait') {
          steps {
            echo 'wait'
          }
        }

        stage('sleep1') {
          steps {
            sleep 3
          }
        }

        stage('sleep5') {
          steps {
            sleep 1
          }
        }

        stage('sleep7') {
          steps {
            sleep 1
          }
        }

        stage('sleep8') {
          steps {
            sleep 1
          }
        }

        stage('sleep10') {
          steps {
            sleep 1
          }
        }

        stage('sleep11') {
          steps {
            sleep 1
          }
        }

        stage('sleep12') {
          steps {
            sleep 1
          }
        }

        stage('sleep13') {
          steps {
            sleep 1
          }
        }

        stage('sleep14') {
          steps {
            sleep 5
          }
        }

      }
    }

    stage('print') {
      steps {
        echo 'print'
      }
    }

  }
  environment {
    env1 = 'env2'
  }
}