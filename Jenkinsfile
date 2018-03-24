pipeline {
    agent any 
    stages {
	
        stage('Build') { 
            steps {
              withMaven(maven : 'Maven')
		    bat 'mvn clean'
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
