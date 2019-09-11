pipeline {
    agent none
    stages {
        stage('Integration- Tests') {
            agent {label 'master'}
            steps {
                sh 'ls -l'
                sh 'npm --version'
            }
        }
    }
}
