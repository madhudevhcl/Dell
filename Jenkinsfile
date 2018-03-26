pipeline {
    agent any 
    stages {
	
		    
        stage('Build') { 
            steps {
		    
		    withEnv([“PATH+MAVEN=${tool `maven-3.5.3`
}/bin”])
              withMaven(maven : 'Maven-3.5.3')
		    bat 'mvn compile'
            }
        }
        stage('Test') { 
            steps {
               echo " Test success" 
            }
        }
        stage('Deploy') { 
            steps {
                echo " Deploy success" 
            }
        }
    }
}
