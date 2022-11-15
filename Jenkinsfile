pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh ' sh "mvn clean package"'
          }
        }

        stage('') {
          steps {
            echo 'completed'
          }
        }

      }
    }

  }
}