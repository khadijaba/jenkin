<<<<<<< HEAD
pipeline {
    agent any

    tools {
        jdk 'JAVA_HOME'
        maven 'M2_HOME'
    }

    stages {

        stage('GIT') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/khadijaba/jenkin.git'
            }
        }

        stage('Compile Stage') {
            steps {
                sh 'mvn clean compile'
            }
        }
    }
=======
pipeline{
>>>>>>> 1468365 (Initial commit: projet Maven avec Jenkinsfile)
}
