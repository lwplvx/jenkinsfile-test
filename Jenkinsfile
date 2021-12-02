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
  stages {
    stage('Deploy') {
      steps {
        echo "Deploy PROJECT is ${MY_PROJECT}"
        echo "Deploy TEAM is ${MY_TEAM}"
        step {
          echo "step AAA"
          echo "step BBB"
      }
      }
    }
  }
  environment {
    MY_PROJECT = 'project-CI-Learning'
    MY_TEAM = 'team-CI-Learning'
  }
}
