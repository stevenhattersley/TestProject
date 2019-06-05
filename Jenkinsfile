pipeline {
  agent any
  stages {
    stage('Git Pull'){
      node(Node 1){
        steps {
        //sh 'cd /home/centos/Git_Repos/TestProject'
        //sh label: '', script: 'cd /home/centos/Git_Repos/TestProject'
        //cd /home/centos/Git_Repos/TestProject
        sh "pwd"
        //dir("/home/centos/Git_Repos/TestProject"){
        //  sh "pwd"
        //}
        //sh 'git pull'
        //sh label: '', script: 'git pull'
        //git pull
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