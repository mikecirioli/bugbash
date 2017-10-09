pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'hi there'
      }
    }
    stage('wait') {
      steps {
        sleep 5
      }
    }
    stage('destroy') {
      steps {
        echo 'goodbye'
      }
    }
  }
}