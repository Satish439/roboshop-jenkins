pipeline {
  agent any
  options {
    ansiColor('xterm')
  }
  stages {
    stage('create jobs') {
      steps {
        sh 'ansible-playbook create-jobs.yml'
      }
    }
  }
}