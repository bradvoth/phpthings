pipeline {
  agent none
  stages {
    stage('Back-end') {
      agent {
        docker { image 'phpunit/phpunit' }
      }
      steps {
        sh 'HOME=/tmp composer install'
      }
    }
  }
}
