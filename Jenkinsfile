def file1


pipeline {

agent any

stages{

stage("Build"){
steps{
script{
   echo "echo"
   file1 = readYaml file: "input_template.yaml"
   echo "file1" + file1
     
  
}
}
   stage("Reading attribute from yaml")
   {
      sh '''
      echo file1[app]
      
      '''
   }
}
}
}


