node{
   stage('SCM Checkout'){   
     git 'https://github.com/herkuswanto/my-app'
   }
   stage('Compile-Package'){
      //test
     def mvnHome = tool name: 'maven3', type: 'maven'
      sh "${mvnHome}/bin/mvn package" 
   }
}
