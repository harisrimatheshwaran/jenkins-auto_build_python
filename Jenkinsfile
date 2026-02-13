pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/harisrimatheshwaran/jenkins-auto_build_python.git'
            }
        }

        stage('Build & Run') {
            steps {
                sh 'python3 nano.py'
            }
        }
    }
}
