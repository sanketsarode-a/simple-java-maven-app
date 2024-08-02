pipeline {
    agent any
    tools {
        maven 'Maven 3.9.2' // Ensure this matches the name used in Global Tool Configuration
    }
    stages {
        stage('Build') {
            steps {
                // Set up Maven environment if needed
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
