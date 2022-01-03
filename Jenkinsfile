pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hello World'
          }
        }

        stage('ParalleleBuild') {
          steps {
            echo 'prout'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Ceci est un test'
      }
    }

    stage('Deploy') {
      steps {
        echo 'C\'est déployé (oupas)'
      }
    }

  }
}