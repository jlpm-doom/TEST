pipeline {
  agent any
  stages {
    stage('Ping') {
      steps {
        sh 'ansible all  -i /etc/ansible/hosts -m ping -f 5 -u jlpm'
      }
    }

  }
}