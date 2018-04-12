library 'SharedLibs'

pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
    
    
  }
  stages {
    stage('Maven Version') {
      steps {
        powershell(script: 'Write-Host "waaah"', returnStatus: true, returnStdout: true)
      }
    }
  }
}
