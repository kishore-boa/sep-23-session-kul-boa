pipeline {
  agent any
  stages {
    stage ('Configure Environment') {
      steps {
        sh 'ansible-playbook myPlaybook.yaml'
      }
    }
  }
}