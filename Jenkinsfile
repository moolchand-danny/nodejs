pipeline {
  agent any
  stages {
    stage('Build') {
      agent {
        node {
          label 'node'
        }

      }
      steps {
        sh 'npm install'
      }
    }
  }
  tools {
    nodejs 'node'
  }
}