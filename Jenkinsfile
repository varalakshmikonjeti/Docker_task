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
        sh 'bash shell.sh'
      }
    }
  }
}
