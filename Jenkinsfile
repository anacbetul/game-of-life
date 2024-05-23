pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Run in background') {
    steps {
        bat 'start javaw -jar your-application.jar'
    }
}

    }
}
//yorum satiriii