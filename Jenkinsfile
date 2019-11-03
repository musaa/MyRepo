pipeline {
    agent { docker { image 'maven:3.6.1' } }
    stages {
        stage('build') {
            steps {
                cmd 'mvn --version'
            }
        }
    }
}
