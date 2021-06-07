pipeline {
  agent {label 'linux'}
  options {
    buildDiscarder(logRotator(numToKeepStr: '5'))
  }
  stages {
    stage('stage-1') {
      steps {
        sh 'echo stage-1'
      }
    }
    stage('stage-2') {
      steps {
        sh 'echo stage-2'
      }
    }
  }
}
