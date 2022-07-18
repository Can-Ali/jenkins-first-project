pipeline {
    agent any // { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Pipeline job with Jenkinsfile"
                sh 'echo using shell within Jenkinsfile'
                sh 'java Hello.java'
                sh 'javac Hello'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
