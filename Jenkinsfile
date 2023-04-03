pipeline {
  agent {
    dockerfile {
      filename 'dockerfile'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'docker run hello-world'
      }
    }

  }
}