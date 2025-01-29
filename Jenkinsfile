pipeline {
    agent any

    stages {
        stage('Build') {
            agent {
                docker {
                    image 'ubuntu'
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
