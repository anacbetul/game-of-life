pipeline{
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
        stage('Run in background') {
            steps {
bat 'start javaw -jar game-of-life.jar'
            }
        }
    }
} 

