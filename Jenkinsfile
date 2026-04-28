pipeline {
    agent { label 'linux' }

    stages {
        stage('Run App') {
            steps {
                sh 'which git'
                sh 'git --version'
                sh 'python3 app.py'
            }
        }
    }
}
