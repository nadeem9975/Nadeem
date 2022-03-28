pipeline {
  agent any
  stages {
    stage('bulid') {
      parallel {
        stage('bulid') {
          steps {
            sh 'pwd'
          }
        }

        stage('test') {
          steps {
            echo 'hello'
          }
        }

      }
    }

    stage('deployment') {
      steps {
        sh 'echo ""hii'
      }
    }

  }
}