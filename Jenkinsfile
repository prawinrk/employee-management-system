pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git branch: 'main', url: 'YOUR_GITHUB_REPO_URL'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t employee-app .'
            }
        }

        stage('Stop Old Container') {
            steps {
                sh 'docker stop employee || true'
                sh 'docker rm employee || true'
            }
        }

        stage('Run Container') {
            steps {
                sh 'docker run -d -p 5000:5000 --name employee employee-app'
            }
        }
    }
}


pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git branch: 'main', url: 'YOUR_GITHUB_REPO_URL'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t employee-app .'
            }
        }

        stage('Stop Old Container') {
            steps {
                sh 'docker stop employee || true'
                sh 'docker rm employee || true'
            }
        }

        stage('Run Container') {
            steps {
                sh 'docker run -d -p 5000:5000 --name employee employee-app'
            }
        }
    }
}