pipeline {
  agent none
  stages {
    stage("test") {
      agent { label 'nodejs-app' }
      steps {
        sh 'node --version'
        echo "hello"
      }
    }
  }
}
