node {

   stage('SCM') {
      // git clone
	  git 'https://github.com/DevOpsEnz/Project1-AddressBook.git'
   }
   
   stage ('build the packages') {
      // mvn package
	  sh 'mvn package'
   }

   
   
   stage ('archival') {
     // archiving artifacts
	 archive 'target/*.war'
   }

}
