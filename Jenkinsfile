pipeline {
  agent any
  stages {
    stage('Git Pull'){
      steps {
        sh 'cd /home/centos/Git_Repos/TestProject'
        //sh label: '', script: 'cd /home/centos/Git_Repos/TestProject'
        //cd /home/centos/Git_Repos/TestProject
        //sh 'git pull'
        //h label: '', script: 'git pull'
        //git pull
      }
    }
    stage('Build') {
      steps { 
        sh 'ls' 
      }
    }
  }
}