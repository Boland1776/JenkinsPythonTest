pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'sleep 10'
                sh 'id'
                sh 'uname -a'
                sh 'sleep 30'
                sh 'ifconfig -a'
                sh 'sleep 600'
            }
        }
    }
}
