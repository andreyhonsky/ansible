pipeline {
    agent andreyhonsky
stage ('Deploy nginx to server') {
    steps {
        sh 'ansible-playbook install-nginx.yml -v'
    }
}
}