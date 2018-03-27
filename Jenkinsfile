pipeline {
    agent any 
	tools {
		maven 'Maven-3.5.3'
	}
    stages {
	
	    
        stage('Build') { 
            steps {
		    
		   
            //  withMaven(maven : 'Maven-3.5.3')
		    
		    bat 'mvn validate'
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
