pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'javac Calculator.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java Calculator'
            }
        }
    }
}

