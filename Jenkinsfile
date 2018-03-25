pipeline {
  agent any
  stages {
    stage('1erstage') {
      parallel {
        stage('1erstage') {
          steps {
            echo '1er stage'
          }
        }
        stage('2eme stage') {
          steps {
            echo 'hello'
          }
        }
        stage('3eme stage') {
          steps {
            echo 'hi hi'
          }
        }
      }
    }
  }
}