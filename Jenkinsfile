pipeline {
  agent {
    node {
      label 'java7'
    }

  }
  stages {
    stage('Buzz') {
      steps {
        echo 'This is Buzz'
      }
    }
    stage('2nd stage') {
      steps {
        echo 'This is 2nd'
      }
    }
  }
}