pipeline {
    agent any
    triggers {
        pollSCM('* * * * *') 
    }
    stages {
        stage('Build Info') {
            steps {
                echo "JENKINS_URL: ${env.JENKINS_URL}"
                echo "BUILD_ID: ${env.BUILD_ID}"
            }
        }
    }
}
