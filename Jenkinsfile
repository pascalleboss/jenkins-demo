pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo '📥 Récupération du code depuis GitHub'
            }
        }

        stage('Build') {
            steps {
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                sh 'chmod +x hello.sh'
                sh './hello.sh'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Déploiement simulé'
            }
        }
    }
}
