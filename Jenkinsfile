node('master')
{
	stage('build')
	{
		git url: 'git@github.com:sagardeo21m/SSimpleWebApp.git'
		sh "mvn -f pom.xml clean install"
	}
}

