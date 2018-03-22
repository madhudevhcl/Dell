pipeline {
    agent any 
    stages {
	
        stage('Build') { 
            steps {
              withmaven (maven:Maven)
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
