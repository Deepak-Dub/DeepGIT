pipeline {
    agent {
        docker {
            image 'node:18'
        }
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Check Node') {
            steps {
                sh 'node -v'
            }
        }

        stage('Run App') {
            steps {
                sh 'node app.js'
            }
        }
    }
}
