pipeline {
    agent any 
    tools {
        maven 'Maven 3.8.5'
    }
    stages {
        stage('git clone') {
            steps{
                git 'https://github.com/nagnani/ks.git'
            }
        }
        stage('maven version') {
            steps{
                sh 'mvn --version'
            }
        }
    }
}