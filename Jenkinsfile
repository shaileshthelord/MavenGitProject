pipeline{
      agent any
	      environment {
		  PATH = "/usr/share/maven/bin"
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
