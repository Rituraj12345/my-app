node{
   stage('SCM Checkout'){
     git 'https://github.com/Rituraj12345/my-app/'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: '', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
