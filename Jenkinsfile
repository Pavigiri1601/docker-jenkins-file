pipeline {
  agent any
      stages{
          stage ("docker pull"){
            steps{
                 sh 'docker pull httpd'
             }
              }
          stage ("docker run"){
            steps{
                 sh 'docker run -d --name httpdjenkins -p 5000:80 httpd:latest'
             }
              }
      }
}
