pipeline {
  agent any

  stages {
    stage('Build Project') {
      steps {
        checkout scmGit(branches: [[name: '*/main']], extensions[], userRemoteConfigs:[[url: 'https://github.com/djordi123/jenkins-pipeline']])
      }
    }
  }
}
