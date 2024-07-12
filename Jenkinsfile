pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'test started...'
                sh 'mvn clean test'
            }
        }
    }
}
