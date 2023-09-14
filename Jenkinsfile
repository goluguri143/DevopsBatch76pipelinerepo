pipeline {
  agent any
  stages {
    stage('Plan') {
      steps {
        echo 'I Have a plan to work on CICD'
      }
    }

    stage('Code') {
      steps {
        echo 'I have a Code to work on CICD'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'I Have a Build to Work on CICD'
          }
        }

        stage('Test') {
          steps {
            echo 'I Have a Test To Work On CICD'
          }
        }

        stage('Release') {
          steps {
            echo 'I have a Release On CICD'
          }
        }

        stage('Deploy') {
          steps {
            echo 'I have a Deploy Code on CICD'
          }
        }

        stage('Operate') {
          steps {
            echo 'I have a code to Operate on CICD'
          }
        }

      }
    }

  }
}