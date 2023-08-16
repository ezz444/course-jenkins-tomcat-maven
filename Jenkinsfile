pipeline {
  agent {
    node {
      label 'kubeagent'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'mvn clean package'
      }
    }

  }
  environment {
    jenkins = 'agent'
  }
}