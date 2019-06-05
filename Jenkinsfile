pipeline {
  agent any
  stages {
    stage('Git Pull'){
      steps {
        //sh 'cd /home/centos/Git_Repos/TestProject'
        sh label: '', script: 'cd /home/centos/Git_Repos/TestProject'
        //sh 'git pull'
        sh label: '', script: 'git pull'
      }
    }
    stage('Build') {
      steps { 
        sh 'ls' 
      }
    }
  }
}