 pipeline {
   agent any
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

