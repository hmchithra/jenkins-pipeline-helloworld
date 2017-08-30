pipeline {
    agent { docker 'python' }

    stages {
        stage('build') {
            steps {
                sh 'python hello.py'
            }
        }
    }
}
