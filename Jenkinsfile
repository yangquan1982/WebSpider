pipeline {
    agent {
        docker {
            image 'python:3.7.4' 
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}