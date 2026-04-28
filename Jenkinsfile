pipeline {
    agent { label 'linux' }

    tools {
        git 'git-linux'
    }

    stages {
        stage('Run App') {
            steps {
                sh 'python3 app.py'
            }
        }
    }
}
