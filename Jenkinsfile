pipeline {
    agent { docker 'python' }
    parameters {
        booleanParam(name: 'TRYME', description: 'Just try me!')
    }
    stages {
        stage('build') {
            steps {
                sh 'ls -l'
                sh 'python hello.py'
                sh 'cat Jenkinsfile'
                echo "TRYME ${params.TRYME}"
            }
        }
    }
}
