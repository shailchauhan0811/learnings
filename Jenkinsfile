pipelinne {
  agent {
    docker { image 'node:16-alpine'}
  }
  stages {
    stage('first') {
      steps {
        sh 'node --version'
      }
    }
    stage('second') {
      steps {
        sh 'echo second'
      }
    }
    stage('third') {
      steps {
        sh 'echo third'
      }
    }
  }
}
