pipeline {
   agent any
   options {
       buildDiscarder(logRotator(numToKeepStr:'2'))
   }
   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
   }
}
