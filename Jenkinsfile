pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'sleep 10'
                sh 'ls -R /etc'
            }
        }
    }
}
