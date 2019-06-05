pipeline {
  agent any
  stages {
    stage('Git Pull'){
      steps {
        sh 'cd /home/centos/Git_Repos/TestProject'
        sh 'git pull' 
      }
    }
    stage('Build') {
      steps { 
        sh 'ls' 
      }
    }
  }
}