pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is build number $BUILD_NUMER of demo $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}