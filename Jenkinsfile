pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Show Node') {
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


#yha sesure
