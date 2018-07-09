pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh (script: "mvn -f pom.xml clean install")'
      }
    }
  }
}