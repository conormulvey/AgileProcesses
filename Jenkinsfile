
pipeline {
    agent none 
    stages {
        stage('Build') { 
            steps {
                sh 'python -m py_compile sources/HelloPython.py' 
            }
        }
    }
}
