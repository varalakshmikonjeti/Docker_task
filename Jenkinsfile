pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/varalakshmikonjeti/Docker_task.git'
            }
        }
        stage('build') {
            steps {
                sh 'mvn clean install'
		sh 'python3 python.py'
		sh 'shell.sh'
            }
        }
       
    }
}
