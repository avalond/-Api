pipeline {
  agent any
  stages {
    stage('clone code') {
      steps {
        git(url: 'git@github.com:avalond/e2eForReactNative.git', branch: 'master', poll: true, changelog: true)
      }
    }
  }
}