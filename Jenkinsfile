node{
   stage('SCM Checkout'){
     git 'https://github.com/arp18/javahometech_my-app'
   }
   stage('Compile-Package'){
      // Get maven home path
      tool name: 'Maven-3', type: 'maven'
      sh 'mvn clean install package'
     
   }
}
