pipeline {
  agent {
    docker {
      image 'node:lastest'
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