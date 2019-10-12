node{
   stage('SCM Checkout'){
     git 'https://github.com/herkuswanto/my-app'
   }
   stage('Compile-Package'){
    sh 'mvn package' 
   }
}
