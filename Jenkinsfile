pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/otter2017/config', branch: 'master')
      }
    }
    stage('print') {
      steps {
        echo 'fetch end'
      }
    }
  }
}