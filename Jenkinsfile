pipeline {
    agent { docker { image 'python:2.7.13' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh '''
                     echo "Multiline shell steps
                     ls -lah
                '''
            }
        }
    }
}
