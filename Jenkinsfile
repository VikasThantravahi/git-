pipeline {
    agent {
        docker { image 'alpine:latest' }
        //docker { image 'node:20.10.0-alpine3.18' }
    }
    stages {
        stage('Clone') {
            steps {
                sh 'apk add sudo'
                sh 'sudo apk add git'
                //sh 'apt install git -y '
                sh 'git clone https://github.com/VikasThantravahi/git-.git'
                sh 'ls -lrt'
                sh 'cat /etc/os-release'
            }
        }
        stage('Test') {
            steps {
                //sh 'node --version'
                sh 'cat /etc/os-release'
                sh 'echo "success_________________________>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>"'
            }
        }
    }
}
