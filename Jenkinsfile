pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "This is built $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    Demo = '1'
  }
}