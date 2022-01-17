pipeline {
   agent any
  // environment {
  //     def branchName = '${BRANCH_NAME}'                              
  // }
   stages {
       stage('Print variables') {
           steps {
               echo "${env.BRANCH_NAME}"
               echo "PR id : ${env.CHANGE_ID}"
               echo "Branch name : ${env.BRANCH_NAME}"
               echo "Target branch name : ${env.CHANGE_TARGET}"
           }
       }
   }
}