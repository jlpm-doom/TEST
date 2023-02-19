pipeline {
  agent any
  stages {
    stage('Ping') {
      steps {
        sh '''ansible all   -i 192.168.0.5 -m ping 
'''
      }
    }

  }
}