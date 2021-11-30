pipeline {
    agent any
    environment {
        MY_PROJECT = 'project-1'
        MY_TEAM    = 'team-1'
    }
    stages {
        stage('Build') {
            steps {
 
                echo "MY_PROJECT is ${MY_PROJECT}"
                echo "MY_TEAM is ${MY_TEAM}"
                // 输出内容如下所示：
                // MY_PROJECT is project-1
                // MY_TEAM is team-1
            }
        }
    }
}
