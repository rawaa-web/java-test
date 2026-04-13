pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo "Code déjà récupéré depuis GitHub"
            }
        }

        stage('Compile') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
