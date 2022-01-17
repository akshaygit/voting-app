pipeline {
   agent any
   environment {
       def branchName = ${BRANCH_NAME}                              
   }
   stages {
       stage('Print variables') {
           steps {
               echo env.branchName
           }
       }
   }
}