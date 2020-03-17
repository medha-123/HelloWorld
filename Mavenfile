pipeline {
   agent any

   stages {
      stage('Packaging') {
         steps {
		 
             clean
             compile
             install
			
         }
      }
       stage('Transfer') {
         steps {
		 
            copy "C:\Program Files (x86)\Jenkins\workspace\MyMavenBuild\maven-demo\target\maven-demo-0.0.1-SNAPSHOT.jar" C:\Users\medha\Desktop\Final
         }
      }
       
	  
   }
}