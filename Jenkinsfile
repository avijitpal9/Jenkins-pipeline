@Library('pipeline-library')_
pipeline {
  agent any
  stages {

    stage('Build') {
      steps {
        echo 'Build Stage'
        sayHello 'Avijit'
      }
    }

    stage('Test') {
      steps {
        echo 'Test Stage'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy Stage'
      }
    }

  }
}
