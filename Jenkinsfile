pipeline {
    agent any

    stages {
        stage('Build') {
            agent {
                docker {
                    docker dind
                    image 'node:22.13.1-alpine3.21'
                    reuseNode true
                }
            }
            steps {
                sh '''
                    ls -la
                   
                '''
            }
        }
    }
}
