pipeline {
  agent any
  stages {
    stage('stage') {
      steps {
        echo 'This is $BUILD_NUMBER and value is $DEMO'
      }
    }

  }
  environment {
    DEMO = 'awesome'
  }
}