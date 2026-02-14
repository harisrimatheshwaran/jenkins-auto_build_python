pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building project'
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
