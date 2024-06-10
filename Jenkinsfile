pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        git branch: 'maven-b', url: 'https://github.com/varalakshmikonjeti/Docker_task.git'
        sh 'mvn clean install'
      }
    }
       stage ('shell') {
      steps {
        git branch: 'shellscript_branch', url:  'https://github.com/varalakshmikonjeti/Docker_task.git'
        sh 'bash shell.sh'
      }
    }
    stage ('python') {
      steps {
        git branch: 'python', url:  'https://github.com/varalakshmikonjeti/Docker_task.git'
        sh 'python3 python.py'
      }
    }
  }
}
