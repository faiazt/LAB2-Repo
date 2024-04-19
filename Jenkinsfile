pipeline {
    agent any
    stages {
        stage('Display Jenkins URL') {
            steps {
                echo "Jenkins URL: ${env.JENKINS_URL}"
            }
        }
        stage('Display BUILD_ID') {
            steps {
                echo "BUILD_ID: ${env.BUILD_ID}"
            }
        }
    }
}
