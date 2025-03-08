pipeline {
    agent any

    stages {
        stage('Build') {
            ajent{
                docker{
                    image 'node:18-alpine'
                    reuseNode true
                }
            }
            steps {
                sh '''
                    ls -la
                    node --version
                '''
            }
        }
    }
}