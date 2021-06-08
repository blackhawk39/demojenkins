pipeline {
    agent { any tools {jdk'JDK15'} }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'mvn clean install'
            }
        }
    }
}
