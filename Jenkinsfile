pipeline {
agent any
stages {
        stage('download git_repository') 
{
steps {
       git branch: 'new-repo', url: 'https://github.com/andreyhonsky/ansible.git'
      }
}
stage('Execute ansible playbook') {
steps {
sh 'ansible-playbook install-nginx.yml -vv'
}
}
}
}