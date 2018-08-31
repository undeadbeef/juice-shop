pipeline {
  agent {
    docker { image 'node:carbon' }
  }
  stages {
    stage('build') {
      steps {
        sh 'npm --version'
        sh 'npm install'
      }
    }

    stage('test') {
      steps {
        sh 'npm test'
      }
    }
  }
}
