pipeline {
    agent any
    
     stages {
        stage('Pull GIT') {
            steps {
                echo 'Pulling...';
                  git branch: 'master',
                  url : 'https://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@github.com/slowwslothh/myapp.git',
                  credentialsId: 'githubtoken';
            }
        }
        }
        }
