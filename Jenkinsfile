pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Samarth1080p/devvlab.git'
            }
        }

        stage('Build') {
            steps {
                echo "No build needed for HTML"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy success"
            }
        }
    }
}