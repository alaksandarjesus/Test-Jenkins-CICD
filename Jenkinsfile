pipeline {
    agent any

    stages {

        stage('Deploy') {
            steps {
                bat 'docker compose down'
                bat 'docker compose up -d --build'
            }
        }

    }
}