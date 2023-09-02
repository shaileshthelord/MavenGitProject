pipeline{
      agent any
	      environment {
		  PATH = "/usr/share/maven-3.0.5/bin"
		  }
         stages{
		       stage ('Get Code'){
			         steps{
					    git branch:'master',
						url:'https://github.com/shaileshthelord/MavenGitProject.git'
			            
			              }
					   }
					   
			   stage('Build'){
			          steps{
					     sh 'mvn clean package'
						   }
					  }
			      }
			   
}
