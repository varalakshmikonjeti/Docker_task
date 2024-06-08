pipeline {
    agent {
	    label 's1'
    }

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/varalakshmikonjeti/Docker_task.git'
                sh "python3 main.py"
		        sh "shell.py"
            }
        }
    }
}
