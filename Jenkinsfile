pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'javac Encrypt.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Encrypt'
            }
        }

    }
}
