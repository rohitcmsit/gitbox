node {
   def mvnHome
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git 'https://github.com/rohitcmsit/gitbox.git'
      // Get the Maven tool.
      // ** NOTE: This 'M3' Maven tool must be configured
      // **       in the global configuration.           
     
   }
   stage('Build') {
         echo "from Git"
   }
   stage('Results') {
       build job: "gitpush"     
   }
}
