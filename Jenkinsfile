pipeline {
  agent any
  stages {
    stage('Git Pull'){
      node('Node 1'){
        steps {
        sh 'ls'
        }
      }
    }
    stage('Build') {
      steps { 
        sh 'ls' 
      }
    }
  }
}