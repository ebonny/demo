pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/ebonny/demo.git'
            }
        }
        stage('Build') {
            steps {
                gradle clean build
            }
        }

    }
}