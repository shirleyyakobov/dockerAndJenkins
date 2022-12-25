pipeline{
    agent any 
    stages{
        stage('node') {
            agent {
                docker {image 'node:alpine3.16'}
            }
            steps {
                sh 'node --version'
            }
        }
        stage('python'){
            steps {
                sh 'python3 --version'
            }
        }
    }
}