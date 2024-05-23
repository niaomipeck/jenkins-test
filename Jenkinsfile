pipeline {
    agent { docker { image 'maven:3.9.6-eclipse-temurin-21-alpine' } }
    stages {
        stage('build') {
            steps {
                echo 'Hello World!'
                sh 'mvn --version'
            }
        }
    }
}
