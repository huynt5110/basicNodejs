pipeline {
  agent any
    
  tools {
      nodejs "16.6.2"
  }
    
  stages {
    stage("verify tooling") {
      steps {
        sh '''
          docker version
          docker info
          docker compose version 
          curl --version
          jq --version
        '''
      }
    }
  }
}