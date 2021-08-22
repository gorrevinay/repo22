node('master') 
{  
  stage ('continuous Download')
  {
  git https://github.com/sunildevops77/maven.git'
  }
  stage('continuos build')
	sh label: '',script: 'mvn package'
	}
}
