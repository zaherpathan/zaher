pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''mvn package
'''
      }
    }

    stage('download') {
      steps {
        sh 'echo "hello download"'
      }
    }

  }
  environment {
    Build = ''
  }
}