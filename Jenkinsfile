pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "${env.CHANGE_ID}"'
            }
        }
    }
}
