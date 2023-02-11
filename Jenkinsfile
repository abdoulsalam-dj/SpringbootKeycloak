pipeline {
    agent any
    stages {
        stage(‘Build’) {
            steps {
                 bash "C:/apache-maven-3.8.6/bin/mvn clean package"
            }
        }
        stage(‘Test’) {
            steps {
                 bash "C:/apache-maven-3.8.6/bin/mvn test"
            }
        }

    }
}
