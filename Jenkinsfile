pipeline {
    agent any 
    stages {
	
	    
        stage('Build') { 
            steps {
		    
		   
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
