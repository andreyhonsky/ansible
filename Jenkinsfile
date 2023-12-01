pipeline {
    agent any
        options {
        ansiColor('xterm') 
        }
    stages {
        stage('Deploy nginx to server') {
            steps {
                ansiColor('xterm') {
                    sh 'ansible-playbook install-nginx.yml -v'
               }
            }
        }
    }
}
