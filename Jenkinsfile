pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/girixxz/tugas_devops_p1.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
