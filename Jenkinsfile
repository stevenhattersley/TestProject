// This file is run when thr Git repo changes.
// The Git repo is auto pulled at /var/lib/jenkins/workspace/...pipeline_name...
pipeline {
  agent any
  stages {
    stage('Copy python files'){
      steps {
        //sh 'ls'
        sh 'cp ./TestFile3 /opt/JenkinsTest'
      }
    }
    stage('Run unit test script') {
      steps { 
        sh 'ls' 
        sh '/usr/bin/python /opt/JenkinsTest/Unit.py' / Works but puts results in working space
        //sh 'python /var/lib/jenkins/workspace/Unit.py' //Works but puts results in working space
        //sh 'python /var/lib/jenkins/workspace/Test_Pipeline_2_master/Unit.py' //This works
      }
    }
  }
}