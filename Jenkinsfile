pipeline {
  agent {
    docker {
      image 'new_image_test'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'echo "hello World"'
      }
    }
  }
}