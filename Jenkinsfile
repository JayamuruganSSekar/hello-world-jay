node{
   stage('SCM Checkout'){
     git 'https://github.com/JayamuruganSSekar/hello-world-jay'
   }
   stage('Compile-Package'){
    
      def mvnHome =  tool name: 'maven-3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
    }
    stage
