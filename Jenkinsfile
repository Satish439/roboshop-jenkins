pipeline{
  agent any
  stages{
    stage('Create jobs'){
      steps{
        sh 'ansible-playbook create-jobs.yml'
      }
    }
  }
}