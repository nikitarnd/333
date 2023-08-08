pipeline {
  agent any
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

        stage('sleep2') {
          steps {
            sleep 1
          }
        }

        stage('sleep3') {
          steps {
            sleep 1
          }
        }

        stage('sleep4') {
          steps {
            sleep 1
          }
        }

        stage('sleep5') {
          steps {
            sleep 1
          }
        }

        stage('sleep6') {
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

        stage('sleep9') {
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
            sleep 13
          }
        }

      }
    }

    stage('end') {
      steps {
        echo 'end'
      }
    }

    stage('123') {
      steps {
        build(job: '321312', propagate: true, wait: true, quietPeriod: 1)
      }
    }

    stage('deploy') {
      steps {
        waitForBuild(runId: '3321', propagate: true)
      }
    }

  }
}