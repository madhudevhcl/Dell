pipeline {
    agent any 
    stages {
	
        stage('Build') { 
            steps {
              
	    bat 'mvn verify'
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
