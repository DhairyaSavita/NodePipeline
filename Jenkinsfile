pipeline {
  agent any
  tools {
    nodejs '24.8.0' // This name must match the name you set in step 4
  }
  stages {
    stage('Build and Test') {
      steps {
        sh 'npm install'
        sh 'npm test'
      }
    }
  }
}