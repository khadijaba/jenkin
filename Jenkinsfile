pipeline {
    agent any

    tools { 
        jdk 'JAVA_HOME'    // nom du JDK configuré dans Jenkins
        maven 'M2_HOME'    // nom de Maven configuré dans Jenkins
    }

    stages {
        stage('GIT') {
            steps {
                // Récupère le code depuis Git
                git branch: 'master',
                    url: 'https://github.com/hwafa/timesheetproject.git'
            }
        }

        stage('Compile Stage') {
            steps {
                sh 'mvn clean compile'
            }
        }
    }
}
