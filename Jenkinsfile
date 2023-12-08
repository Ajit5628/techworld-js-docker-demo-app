pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo 'building the application...'
            }
        }
        stage("test") {
            steps {
                echo 'testing the application...'
                echo 'application build'
            }
        }
        stage("deploy") {
            steps {
                echo 'deploying the application...'
            }
        }
        stage("QC") {
            steps {
                echo 'QC the application...'
            }
        }
    }
}
