node('master')
{
	stage('build')
	{
		git url: 'git@github.com:sagardeo21m/SimpleWebApp.git'
		sh "mvn -f pom.xml clean install"
	}
}

