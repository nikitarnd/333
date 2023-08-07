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

        stage('sleep') {
          steps {
            sleep 3
          }
        }

      }
    }

    stage('end') {
      steps {
        echo 'end'
      }
    }

  }
}