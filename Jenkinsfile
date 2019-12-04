
pipeline {
    agent none 
    stages {
        stage('Build') { 
            steps {
                bat 'python -m py_compile sources/HelloPython.py' 
            }
        }
    }
}
