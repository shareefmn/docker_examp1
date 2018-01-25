pipeline {
    agent { label 'apache' }
    stages {
        stage('Test') {
            agent { dockerfile true }
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
