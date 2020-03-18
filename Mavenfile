pipeline {
   agent any

   stages {
      stage('Packaging') {
         steps {
		     bat "cd C:\\Users\\medha\\eclipse-workspace\\maven-demo"
			 
			 mvn clean
             mvn compile
             mvn install
		
			
         }
      }
       stage('Transfer') {
         steps {
		 
            echo "Transfer"
         }
      }
       
	  
   }
}