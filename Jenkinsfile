pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "MY_PROJECT is ${MY_PROJECT}"
        echo "MY_TEAM is ${MY_TEAM}"
      }
    }

  }
  environment {
    MY_PROJECT = 'project-1'
    MY_TEAM = 'team-1'
  }
}