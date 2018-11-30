node{
   stage('SCM Checkout'){
     git 'https://github.com/nehasai/my-app.git'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'LocalMaven', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
  
}




