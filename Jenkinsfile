pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "This is built $BUID_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    Demo = '1'
  }
}