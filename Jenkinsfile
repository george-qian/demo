pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git(branch: 'master', changelog: true, url: 'https://github.com/jenkinsci/pipeline-plugin.git')
      }
    }
  }
}