pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/ramyachetty/maven-project-utils.git'
            }
        }
        stage('build') {
            steps {
                sh 'mvn clean install'
            }
        }
       
    }
}
