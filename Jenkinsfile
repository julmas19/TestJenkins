Jenkinsfile (canalización declarativa)
pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
    stages {
        stage('build') {
            steps {
                bat 'java -version'
            }
        }
    }
}
