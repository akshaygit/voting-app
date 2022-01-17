pipeline {
   agent any
   environment {
       branchName = ${BRANCH_NAME}                              
   }
   stages {
       stage(Print variables) {
           steps {
               echo env.branchName
           }
       }
   }
}