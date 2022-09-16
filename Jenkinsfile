pipeline {
  agent any
    
  tools {
      nodejs "16.6.2"
  }
    
  stages {
    stage("verify tooling") {
      steps {
        sh '''
          docker compose up -d
        '''
      }
    }
  }
}