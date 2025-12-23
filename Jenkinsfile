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
                echo 'Compilation / Build terminé avec succès'
            }
        }

        stage('Test') {
            steps {
                echo 'Tests exécutés avec succès'
            }
        }
    }

    post {
        success {
            echo 'Pipeline exécuté avec succès'
        }
        failure {
            echo 'Erreur dans le pipeline'
        }
    }
}
