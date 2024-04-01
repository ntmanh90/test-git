/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('Git clone') {
            steps {
                git credentialsId: 'ntmanh90-github', url: 'https://github.com/ntmanh90/test-git'
            }
        }
        stage('Test') {
            steps {
                echo "Testing completed"
            }
        }
        stage('Build') {
            steps {
                echo "Build completed"
            }
        }
    }
}
