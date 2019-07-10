pipeline {

agent any

environment {
def sai='koti'
}

  stages {
  
    stage ('check bat') {
      steps {
      script {
            bat label: '', returnStdout: true, script: '@Build.bat'
      }
      }
    
    }
  }
  
}
