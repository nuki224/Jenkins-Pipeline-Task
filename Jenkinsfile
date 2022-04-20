pipeline {
  agent any
  stages {
    stage('Running Project') {
      steps {
        sh '''mvn --version
git --version
java --version'''
      }
    }

    stage('Build Step') {
      steps {
        sh 'mvn compile test package '
      }
    }

  }
}