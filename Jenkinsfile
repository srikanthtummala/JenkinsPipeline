pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        bat 'echo "Hello World."'
        bat 'echo "${env.WORKSPACE}"'
      }
    }
  }
}