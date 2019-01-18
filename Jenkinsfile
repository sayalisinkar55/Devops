  node{
   stage('SCM Checkout'){
     git 'https://github.com/sayalisinkar55/Devops'
   }
   stage('Compile-Package'){
    
      def mvnHome =  tool name: 'maven', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
}


