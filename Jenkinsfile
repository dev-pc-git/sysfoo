pipeline{

  agent any
 
  tools{
   
   maven 'Maven 3.6.3'
}
 
  stages{

     stage('build'){
     steps{
      sh 'mvn compile'

      }
   } 

   stages{

     stage('test'){
     steps{
      sh 'mvn clean test'

      }
   }
 stages{

     stage('package'){
     steps{
      sh 'package -DskipTests'

      }
   }


  }


}
