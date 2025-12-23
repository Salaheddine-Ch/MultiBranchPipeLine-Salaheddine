pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Build OK'
            }
        }

        stage('Test') {
            steps {
                echo 'Tests OK'
            }
        }
    }
}
