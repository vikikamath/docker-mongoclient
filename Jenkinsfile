/*
pipeline {
  agent { 
    dockerfile true 
  }
  stages {
    stage('Mongo Client Test') {
      steps {
        sh ''
        sh 'mongo -version'
      }
    }
  }
}
*/

node {
  stage('Mongo Client Test') {
    docker.image('mongoclient/mongoclient').inside {

      stage("Print Version") {
        sh "mongo -version"
      }
    }
  }
}

