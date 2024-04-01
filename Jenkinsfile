/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.9.6-eclipse-temurin-17-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
/*Tôi dự định sẽ bổ xung thêm state tại đây*/
/*Toi vừa bổ xung commit*/
