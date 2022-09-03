pipeline{

  agent {
    node {
      label 'workstation'
    }
  }

  environment{
    SSH=credentials('SSH')
  }

  parameters {
     string(name: 'COMPONENT', defaultValue: '',description: 'which component to run in pipeline')
  }

  stages {
    stage('Ansible playbook') {
      steps {
        sh 'ansible-playbook -i'
      }
    }
  }
