pipeline {
  agent {
    node {
      label 'aaa'
    }
    
  }
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/klarna/HiveRunner.git', branch: 'HDP2.6.3', changelog: true, poll: true)
      }
    }
  }
}