pipeline {
  agent any
  stages {
    stage('git-pull-and-build') {
      steps {
        git(url: 'https://github.com/SWEDemo/CICD.git', branch: 'master')
      }
    }

  }
}