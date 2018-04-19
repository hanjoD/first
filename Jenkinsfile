pipeline {
  agent none
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'huhu'
          }
        }
        stage('build para') {
          steps {
            sleep 5
          }
        }
      }
    }
    stage('eat') {
      steps {
        sh 'echo \'mee\''
      }
    }
  }
}