
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Python project'
                sh 'python3 program.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing project'
                sh 'python3 -m py_compile program.py'
            }
        }
    }
}
