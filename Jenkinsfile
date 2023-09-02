pipeline{
      agent any
	      environment {
		  PATH = "$PATH:/opt/apache-maven-3.9.4/bin"
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
