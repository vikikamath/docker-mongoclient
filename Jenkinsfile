pipeline {
  agent { 
    dockerfile true 
  }
  stages {
    stage('Mongo Client Test') {
      steps {
        sh ''
        sh 'mongo -v'
      }
    }
  }
}
