pipeline {
    agent {
        docker { image 'node:20.10.0-alpine3.18' }
    }
    stages {
        stage('Clone') {
            steps {
                sh 'apk add git'
                sh 'git clone https://github.com/VikasThantravahi/git-.git'
                sh 'ls -lrt'
            }
        }
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'cat /etc/os-release'
                sh 'echo "success_________________________>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>"'
            }
        }
    }
}
