pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Step for build stage'
          }
        }
        stage('Test') {
          steps {
            echo 'Step for Testing'
          }
        }
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy stage'
      }
    }
  }
}