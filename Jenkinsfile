pipeline {
    agent { /usr/local/bin/docker { image 'node' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'node --version'
            }
        }
    }
}
