pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build .Net Application '
          }
        }

        stage('Test') {
          steps {
            echo 'Test .net Application'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy app to docker hub'
      }
    }

  }
}