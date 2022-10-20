pipeline {
  agent any
  
  stages {
    stage('build') {
      steps {
        jar -cvf SWE645.war *
      }
    }
    stage('test') {
      steps {
        echo 'testing application'
      }
    }
    stage('deploy') {
      steps {
        echo 'deploying application'
      }
    }
  }
}
