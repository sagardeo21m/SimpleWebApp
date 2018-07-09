node('master')
{
	wrap([$class: 'BuildUser']) {
			
			cleanWs()
			def workspace = pwd()
			
			stage('Source Code Checkout') {
				//println "Source Code Checkout"
				git url:'https://github.com/sagardeo21m/SimpleWebApp.git'
			}
			stage ('Build') {
				//println "Maven Build"
				sh (script: 'mvn -f pom.xml clean install -DREPO_ENV=int')
			}
	}
}
