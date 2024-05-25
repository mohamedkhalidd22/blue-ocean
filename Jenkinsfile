pipeline {
  agent any
  stages {
    stage('bulid') {
      steps {
        echo 'bulid completed'
      }
    }

    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            echo 'test1 running'
          }
        }

        stage('test2') {
          steps {
            echo 'test2 running'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy completed'
      }
    }

  }
}