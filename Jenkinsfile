pipeline {
  agent {
    docker {
      image 'node'
    }

  }
  stages {
    stage('Bootstrap') {
      steps {
        sh 'echo "Hello world"'
      }
    }
  }
}