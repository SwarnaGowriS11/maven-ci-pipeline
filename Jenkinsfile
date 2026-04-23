pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/SwarnaGowriS11/maven-ci-pipeline.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
