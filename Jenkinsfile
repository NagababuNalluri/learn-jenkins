 pipeline {
   agent {
   label "centos8"
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

