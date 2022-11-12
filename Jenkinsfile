pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Check out code'
            }
        }
        stage('test') {
            steps {
                echo 'unit test run'
            }
        }
        stage('build'){
            steps {
                echo 'run build'
            }
        }
        stage('deploy'){
            steps {
                echo 'deploy to k8s'
            }
        }
    }
}