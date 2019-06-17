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
        //sh '/usr/bin/python /opt/JenkinsTest/Unit.py'
      }
    }
  }
}