 pipeline {
   agent {
   label "workstation"
   }
    stages{
       stage('hello'){
           steps{
             echo 'hello from jenkins'
           }
      }
      stage('ok'){
                 steps{
                   echo 'hello from jenkins'
                 }
      }
      stage('bye'){
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

