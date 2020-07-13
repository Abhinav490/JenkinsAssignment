pipeline {
   agent any

   stages {
      stage('new files') {
         steps {
            sh 'touch sample.txt sample2.txt'
         }
      }
      stage('view disk space'){
          steps{
              sh 'df -kh'
          }
      }
      stage('to view processes') {
         steps {
            sh 'ps aux'
         }
      }
   }
}
