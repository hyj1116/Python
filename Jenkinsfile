pipeline {
  agent any
  stages {
    stage('Dev') {
      agent any
      environment {
        Test = 'test'
      }
      steps {
        sh 'ls'
        echo 'hello'
      }
    }
  }
}