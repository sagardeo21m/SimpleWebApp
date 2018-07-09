pipeline {
  agent any
  stages {
    stage('SCM Checkout') {
      steps {
        git url: 'https://github.com/sagardeo21m/SimpleWebApp.git'
      }
    }
    stage('Build') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}
