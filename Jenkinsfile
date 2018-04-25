pipeline {
  agent any
  stages {
    stage('Python test') {
      steps {
        sh 'nosetests --with-xunit'
      }
    }
  }
}