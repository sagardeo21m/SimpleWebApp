pipeline {
  agent any
    stage('Checkout') 
	  {
		git url: 'https://github.com/sagardeo21m/SimpleWebApp.git'
	  }
    stage ('Build') 
	  {
		sh (script: "mvn -f pom.xml clean install -DREPO_ENV=int")
	  }
  }
}
