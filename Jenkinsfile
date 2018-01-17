pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
        stage('echo') {
            steps {
                sh 'echo Hello World'
        }
    }
}
