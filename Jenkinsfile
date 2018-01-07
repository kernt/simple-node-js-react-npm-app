pipeline {
  agent {
    docker {
      image 'node:6'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}