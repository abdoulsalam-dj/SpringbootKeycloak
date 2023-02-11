pipeline {
    agent any
    stages {
        
        stage(‘Checkout’){
            git 'https://github.com/abdoulsalam-dj/SpringbootKeycloak.git'
            mvnHome='C:\apache-maven-3.8.6'
        }
        stage(‘Build’) {
            steps {
                is (isUnix()){
                 sh "C:/apache-maven-3.8.6/bin/mvn clean package"
                }
            }
        }
        stage(‘Test’) {
            steps {
                is (isUnix()){
                 sh "C:/apache-maven-3.8.6/bin/mvn test"
                }
            }
        }

    }
}
