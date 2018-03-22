pipeline {
    agent any 
    stages {
	
        stage('Build') { 
            steps {
              
	    sh 'mvn verify'
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
