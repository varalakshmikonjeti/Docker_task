pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        git branch: 'maven-b', url: 'https://github.com/varalakshmikonjeti/Docker_task.git'
        sh 'mvn clean install'
      }
    }
      stage ('build') {
      steps {
        git 'https://github.com/varalakshmikonjeti/Docker_task.git'
        sh 'python3 python.py'
      }
    }
  }
}
