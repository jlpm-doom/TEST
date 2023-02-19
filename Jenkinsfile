pipeline {
  agent any
  stages {
    stage('Ping') {
      steps {
        sh 'ansible  -i hosts -m ping -f 5 '
      }
    }

  }
}