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
               sh "java -version"
               sh "/home/jenkins/gradle/bin/gradle clean build"
            }
        }

    }
}