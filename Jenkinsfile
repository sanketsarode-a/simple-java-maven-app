pipeline {
    agent any
    environment {
        PATH = "/opt/apache-maven-3.9.2/bin:${env.PATH}"
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}

