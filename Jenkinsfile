pipeline {
    agent any
    options {
        buildDiscarder(logRotator(numToKeepStr: '10'))
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}