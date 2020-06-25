pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'Pipeline from GitHub'
      }
    }

    stage('Shell') {
      steps {
        sh 'echo "Hello, World"'
      }
    }

    stage('pull') {
      steps {
        git(url: 'git@github.com:yashwanthsn2020/yashwanthsn.git', branch: 'master')
      }
    }

  }
}