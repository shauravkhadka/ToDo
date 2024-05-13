pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                // Clone the GitHub repository
                git 'https://github.com/shauravkhadka/your-repo.git'
            }
        }
        stage('Build Docker Image') {
            steps {
                // Build Docker image for Todo List application
                script {
                    docker.build('todo-list-app')
                }
            }
        }
        stage('Push Docker Image') {
            steps {
                // Push Docker image to Docker Hub or your registry
                script {
                    docker.withRegistry('https://registry.example.com', 'credentials-id') {
                        docker.image('todo-list-app').push('latest')
                    }
                }
            }
        }
        stage('Deploy Application') {
            steps {
                // Deploy the updated application using Docker Compose
                sh 'docker-compose up -d'
            }
        }
    }
}
