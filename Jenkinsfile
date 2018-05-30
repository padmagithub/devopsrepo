pipeline {
  agent any
  stages {
    stage('scm') {
      steps {
        git(url: 'https://github.com/padmagithub/devopsrepo', branch: 'master', credentialsId: 'padmagithub')
      }
    }
  }
}