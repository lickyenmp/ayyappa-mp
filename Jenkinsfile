 node {
   
    stage "1. create some dummy folders"
    sh "mkdir -p test-folder"
    sh "cd test-folder"
    sh "touch test.txt"

    stage "2. print the out of the below commands"
    sh "free -m"
    sh "df -h"
    sh "du -ksh"
    sh "uptime"

    stage "3. install required packages"     
    sh "sudo yum install -y git"    
    sh "sudo yum install -y docker"     
    sh "sudo yum install -y httpd" 
}

