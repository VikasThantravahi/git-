pipeline {
    agent {
        docker { image 'gittools/gitversion:6.0.0-beta.3-alpine.3.16-6.0' }
        //docker { image 'node:20.10.0-alpine3.18' }
    }
    stages {
        stage('Clone') {
            steps {
                //sh 'apk add sudo'
                //sh 'sudo apk add git'
               // sh 'apt update'
                //sh 'apt install git -y'
                //sh 'git clone https://github.com/VikasThantravahi/git-.git'
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
