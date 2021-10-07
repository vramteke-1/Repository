pipeline {
    agent any
    stages {                           
        stage('Build') {               
            steps {                        
                echo 'Build the app'
			  }	
             }
		stage('Test') {                
            steps {                     
                echo 'Test the app1'
			  }	
             }
		stage('deploy') {                
            steps {                      
                echo 'deploy the app'
			  }	
              }	 
          }
	 post {
        always {
		echo 'I will always say Hello again!'
        }
    }
}
