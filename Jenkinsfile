pipeline {

   agent any

   stages {
       stage('docker-compose') {
           steps {
              
              sh "/usr/local/bin/docker-compose up -d"
              
           }
       }
   }
     
}