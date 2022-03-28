pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'pwd'
          }
        }

        stage('pro') {
          steps {
            sh 'pwd'
          }
        }

      }
    }

    stage('test') {
      steps {
        sh 'touch f1'
      }
    }

  }
}