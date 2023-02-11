pipeline {
    agent any
    stages {
        stage(‘Build’) {
            steps {
                dir(''){
                    junit "C:/apache-maven-3.8.6/bin/mvn clean package"
                }
            }
        }
        stage(‘Test’) {
            steps {
                  dir(''){
                    junit "C:/apache-maven-3.8.6/bin/mvn test"
                }
            }
        }

    }
}
