pipeline {
  agent {
    dockerfile {
      filename 'dockerfile'
    }

  }
  stages {
    stage('test') {
      steps {
        build 'dockerbuild'
      }
    }
  }
}