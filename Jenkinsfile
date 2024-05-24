
pipeline { agent any stages { stage ('Compile Stage') {

        steps {
            withMaven(maven : 'apache-maven-3.6.1') {
                bat'mvn clean compile'
            }
        }
    }

} }

// pipeline{
//     agent any

//     stages {
//         stage('Build') {
//             steps {
//                 bat 'mvn clean install'
//             }
//         }
//         stage('Test') {
//             steps {
//                 bat 'mvn test'
//             }
//         }
//         stage('Run in background') {
//             steps {
// bat 'start javaw -jar game-of-life.jar'
//             }
//         }
//     }
// } 

