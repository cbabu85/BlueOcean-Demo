pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build my Project'
          }
        }

        stage('Package') {
          steps {
            echo 'Package my Application'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Test My Application'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy to Server'
      }
    }

  }
}