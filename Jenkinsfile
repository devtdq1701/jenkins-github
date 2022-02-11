pipeline {
    String branchName = env.BRANCH_NAME
    String repoUrl = "https://github.com/devtdq1701/jenkins-github.git"
    agent any
    stages {
        stage( 'Clone' ) {
            steps {
                git branch: branchName, url: repoUrl
            }
        }
    }
}