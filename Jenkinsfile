pipeline {
  agent any
  stages {
    stage('Check Any Updates') {
      parallel {
        stage('Check Any Updates') {
          steps {
            git(url: 'https://github.com/TarunUM/temp', branch: 'main')
          }
        }

        stage('') {
          steps {
            echo 'Changes Made in Git '
          }
        }

      }
    }

  }
}