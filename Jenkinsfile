pipeline {
  agent none
  stages {
    stage('Buzz  Buzz') {
      steps {
        echo 'Created a new pipeline '
      }
    }
    stage('Buzz Buzz') {
      parallel {
        stage('Bees Bees ') {
          steps {
            echo 'Buzz Bees, Buzz '
          }
        }
        stage('Bees new') {
          steps {
            echo 'Bees Buzzing'
          }
        }
      }
    }
    stage('prod') {
      steps {
        echo 'this is prod'
      }
    }
  }
}