pipeline {
    agent none
    stages {
        stage('Integration- Tests') {
            agent {label 'master'}
            steps {
                sh 'node --version'
                sh 'ls -l'
            }
        }
    }
}
