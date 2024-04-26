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

        stage('error') {
          steps {
            echo 'Changes Made in Git '
          }
        }

      }
    }

    stage('run name.py') {
      steps {
        sh 'python new.py'
      }
    }

  }
}