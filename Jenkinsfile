pipeline {
    agent any 
	//tools {
		//maven 'Maven-3.5.3'
	//}
    stages {
	
	    
        stage('compile') { 
            steps {
		    
		   
            withmaven(maven :'Maven-3.5.3')
		    
		    bat 'mvn compile'
            }
        }
        stage('Test') { 
            steps {
               bat 'mvn test'
            }
        }
        stage('package') { 
            steps {
               bat 'mvn package' 
            }
        }
    }
}
