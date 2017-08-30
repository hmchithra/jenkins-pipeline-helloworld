pipeline {
    agent { docker 'python' }

    stages {
        stage('build') {
            steps {
                sh 'ls -l'
                sh 'python hello.py'
            }
        }
    }
}
