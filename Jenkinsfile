pipeline {
    agent any

    stages {
        stage('Version') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('welcome') {
            steps {
                sh 'python3 hello_world.py'
            }
        }
    }
}
