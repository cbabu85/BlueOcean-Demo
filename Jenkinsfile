pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build My project'
          }
        }

        stage('Code Analyze') {
          steps {
            echo 'Use SonarQube for Analyzing my Code'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Test my Application'
      }
    }

    stage('Deploy ') {
      steps {
        echo 'Deploy my Application'
      }
    }

  }
}