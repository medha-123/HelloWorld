pipeline {
   agent any

   stages {
      stage('Packaging') {
         steps {
		     bat "cd \\maven-demo"
			 
			 bat "mvn clean"
             bat "mvn compile"
             bat "mvn install"
		
			
         }
      }
       stage('Transfer') {
         steps {
		 
            echo "Transfer"
         }
      }
       
	  
   }
}