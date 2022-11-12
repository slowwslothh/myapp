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
       stage('build')
       {
         steps {
           script{
             sh "ansible-playbook ~/Desktop/myapp/Ansible/build.yml -i ~/Desktop/myapp/Ansible/inventory/host.yml "
       }
       }
       }
  
        }
        }
