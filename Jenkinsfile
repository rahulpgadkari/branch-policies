pipeline {
    agent none
    stages {
        stage("build") {
            steps {
                docker build -t ScannerApi .
            }
        }
    }
}