pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'test starting...'
                sh 'mvn clean test'
            }
        }
    }
}
