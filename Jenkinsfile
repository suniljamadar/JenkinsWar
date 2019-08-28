pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('builds') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}
