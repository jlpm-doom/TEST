pipeline {
  agent any
  stages {
    stage('Ping') {
      steps {
        sh 'ansible all  -m ping -f 5 -u jlpm'
      }
    }

  }
}