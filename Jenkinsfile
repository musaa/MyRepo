pipeline {
    agent { docker { image 'maven:3.6.1' } }
    stages {
        stage('build') {
            steps {
                def mvnHome = tool name:'maven-3.6.1', type:'maven'
                def mvnCMD = "${mvnHome}/bin/mvn"
                sh "${mvnCMD} --version"
            }
        }
    }
}
