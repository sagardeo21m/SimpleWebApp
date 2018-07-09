pipeline {
  agent any
  stages {
    stage("[GitHub] Source Code Checkout") {
				println "Source Code Checkout"
				git branch:master, url:https://github.com/sagardeo21m/SimpleWebApp.git
			}
			stage ("[Maven] Code Build") {
				println "Maven Build"
				sh (script: "mvn -f pom.xml clean install -DREPO_ENV=int")
			}
  }
}
