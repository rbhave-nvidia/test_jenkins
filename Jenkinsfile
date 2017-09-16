pipeline {
  agent none
  stages {
    stage('First Stage') {
      steps {
        build(job: 'TestMask', quietPeriod: 1)
      }
    }
  }
}