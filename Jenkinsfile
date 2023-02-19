pipeline {
  agent any
  stages {
    stage('Ping') {
      steps {
        sh '''ansible all   -i hosts  -m ping 
'''
      }
    }

  }
}