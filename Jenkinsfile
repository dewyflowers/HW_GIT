pipeline {
    agent { docker { image 'golang:1.21.4-alpine3.18' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
