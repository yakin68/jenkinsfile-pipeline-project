pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'python3 pipeline.py'
            }
        }
    }
}
