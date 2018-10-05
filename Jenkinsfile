pipeline {
  agent {
    docker {
      image 'docker.io/node'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'sudo -c "npm install"'
      }
    }
  }
}