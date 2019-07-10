pipeline {

  agent {
   node ('clarity-trunk-ci-ora-Pipeline')
  }

environment {
def sai='koti'
}

  stages {
  
    stage ('check bat') {
      steps {
      script {
            bat label: '', returnStdout: true, script: '@call Build.bat'
      }
      }
    
    }
  }
  
}
