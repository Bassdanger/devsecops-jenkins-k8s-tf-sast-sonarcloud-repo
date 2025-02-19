pipeline {
    agent any
    tools {
        maven 'Maven_3_2_5'
    }
    stages {
       	stage ( "Compile and Run Sonar Analysis" ) {
		steps {
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=jobuggywebapp -Dsonar.organization=devsecopsproject4lizzo -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=42d424ef191da8ddf392dcc2aa51b3883ebaa9ee'
	         	}
	        	}
		}
    }
