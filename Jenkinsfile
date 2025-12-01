pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'   // on Windows
            }
        }
        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
    }
}
