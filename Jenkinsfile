pipeline {	 
    agent any	 
    tools {
    	maven 'my_mvn'
    }
    stages {     	 
    	stage("Compile") {          	 
            steps {             
		sh "mvn compile"          	 
            }     	 
        }     	 
    	stage("Unit test") {          	 
        	steps {               	 
                	sh "mvn test"          	 
            	}     	 
        }	 
    }
}

