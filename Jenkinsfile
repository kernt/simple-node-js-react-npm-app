pipeline {
  agent {
    docker {
      image 'docker.io/node'
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