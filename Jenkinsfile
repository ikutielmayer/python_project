pipeline {
  agent {
    node {
      label 'Nodo A'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'python3 main.py'
      }
    }

  }
}