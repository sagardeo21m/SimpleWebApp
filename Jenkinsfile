pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh \'mvn -f pom.xml clean install\''
      }
    }
  }
}