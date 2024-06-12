pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'This is build stage'
          }
        }

        stage('Test') {
          steps {
            echo 'This is test'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'this is deploy'
      }
    }

  }
}