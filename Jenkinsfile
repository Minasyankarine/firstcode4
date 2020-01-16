pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'Hello-Jenkins', propagate: true, wait: true)
      }
    }

  }
}