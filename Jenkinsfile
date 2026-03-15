pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
             
                git 'https://github.com/souma406/Jenkins.git'
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
