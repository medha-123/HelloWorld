pipeline {
   agent any

   stages {
      stage('Packaging') {
         steps {
		     bat "chalade.bat"
			 
			 // bat "mvn clean"
             // bat "mvn compile"
             // bat "mvn install"
		
			
         }
      }
       stage('Transfer') {
         steps {
		 
            echo "Transfer"
         }
      }
       
	  
   }
}