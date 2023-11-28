pipeline {
agent any
stage('Execute ansible playbook') {
steps {
       sh 'ansible-playbook install-nginx.yml -vv'
}
}
}