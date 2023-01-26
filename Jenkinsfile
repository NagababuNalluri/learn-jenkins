 pipeline {
   agent {
     label 'ansible'
   }
    stages{
       stage('hello'){
           steps{
             echo 'hello from jenkins'
           }
      }
    }

  post{
    always{
      echo 'sending email'
    }
  }
 }

