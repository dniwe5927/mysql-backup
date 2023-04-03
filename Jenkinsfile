pipeline {
  agent {
    dockerfile {
      filename 'docker-compose.yml'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'docker compose build'
      }
    }

  }
}