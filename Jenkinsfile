pipeline {
    agent any
        stages {
            stage ("1. create folder") {
                steps{
                    sh "mkdir -p declarative-folder"
                    sh "cd declarative-folder"
                }
            }
            
            stage ("2. create a file") {
                steps{
                    sh "touch test-file.txt"
                    sh "ls -al"
             stage ("3. create a user") {
                 steps{
                     sh "useradd raj"
                     sh "getent passwd raj"
                        }  
                     }
                }
            }
        }
}
