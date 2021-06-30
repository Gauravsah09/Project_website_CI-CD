pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'Build', propagate: true, quietPeriod: 10)
      }
    }

  }
  environment {
    DEV = 'JDS'
  }
}