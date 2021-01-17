pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sh 'echo Hello'
      }
    }

    stage('step2') {
      steps {
        sh 'echo 2nd-step'
      }
    }

  }
  environment {
    USER = 'JOHNWU94'
  }
}