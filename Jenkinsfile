pipeline {
agent any
stages {
stage ("1.sudo creating a folder"){
steps{
sh "sudo mkdir -p declarative folder"
sh "sudo cd declarative folder"
}
}
stage ("2.creating a file")
steps{
sh "sudo touch test-file.txt"
sh "sudo ls -al"
}
}
}
}


