pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh "behave -i test.feature --junit"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
