pipeline {
  agent any
  stages {
    stage('Running Project') {
      parallel {
        stage('Running Project') {
          steps {
            sh '''mvn --version
git --version
java --version'''
          }
        }

        stage('') {
          steps {
            fileExists 'pom.xml'
          }
        }

      }
    }

    stage('Build Step') {
      steps {
        sh 'mvn compile test package '
      }
    }

  }
}