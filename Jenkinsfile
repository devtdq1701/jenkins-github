pipeline {
    agent any
    environment {
      branchName = "quangtran1701/flask-docker"
      repoUrl = "https://github.com/devtdq1701/jenkins-github.git"
    }
    stages {
        stage( 'Clone' ) {
            steps {
                git branch: ${branchName}, url: ${repoUrl}
            }
        }
    }
}