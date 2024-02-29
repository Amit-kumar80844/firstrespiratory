pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
                // compile code  
	// if successful, move build artifacts to the desired location 
            } 
        } 
        stage('Test') {  
            steps { 
                // check if artifacts are present in the correct location 
	// load test data into the database 
	// execute the test case 
	// continue only if tests passed 
            } 
        }uio 
        stage('Deploy') {  
            steps { 
                // Fetch tested code and deploy it to production 
            } 
        } 
    } 
}
