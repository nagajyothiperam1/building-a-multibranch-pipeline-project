pipeline {
    agent any
    stages {
        stage('echo') {
            steps {
                sh 'echo "Hello world!"'
            }
        }
	stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}
