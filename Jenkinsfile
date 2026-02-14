pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/harisrimatheshwaran/jenkins-auto_build_python.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building project'
            }
        }

        stage('Run Python') {
            steps {
                sh 'python3 nano.py'
            }
        }

        stage('Complete') {
            steps {
                echo 'Pipeline finished successfully'
            }
        }
    }
}

