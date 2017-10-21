pipeline {
  agent none
  stages {
    stage('Back-end') {
      agent {
        docker { image 'phpunit' }
      }
      steps {
        sh 'composer install'
      }
    }
  }
}
