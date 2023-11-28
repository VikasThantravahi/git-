pipeline {
    agent {
        docker { image 'node:20.10.0-alpine3.18' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'cat /etc/os-release'
                sh 'echo "success_________________________>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>"'
            }
        }
    }
}
