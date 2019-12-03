pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Testing'
            }
        }
        stage('Test') {
            steps {
                sh 'make check || true' 
                junit '**/target/*.xml'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
