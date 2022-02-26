pipeline {
  agent any
  stages {
    stage('PIPELINE1') {
      steps {
        build(job: 'JOB_1', propagate: true)
      }
    }

    stage('') {
      steps {
        build(job: 'JOB_2', propagate: true)
      }
    }

  }
}