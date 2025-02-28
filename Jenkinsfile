pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git credentialsId: '5b7455c7-6497-4179-856d-a24eaa413c01', url: 'https://github.com/shivangi-mis/sample.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
