pipeline {
    agent any

    environment {
        APP_ENV = 'development'
    }

    stages {
        stage('Build') {
            steps {
                echo "Building for ${APP_ENV}"
            }
        }

        stage('Test') {
            steps {
                echo "Testing in ${APP_ENV}"
            }
        }
    }
}
