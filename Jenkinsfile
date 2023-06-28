pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo $PWD'
          }
        }

        stage('Test') {
          steps {
            echo 'Hello World'
          }
        }

      }
    }

  }
}