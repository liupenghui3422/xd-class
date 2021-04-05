pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        git(url: 'https://github.com/liupenghui3422/xd-class.git', branch: 'master')
      }
    }

    stage('mvn') {
      steps {
        sh 'mvn clean install'
      }
    }

  }
}