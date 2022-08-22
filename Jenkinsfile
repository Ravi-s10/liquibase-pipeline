def file1
def app
def name
def email
def region

pipeline {

agent any

stages{

stage("Build"){
steps{
                      script{
                             echo "echo"
                             file1 = readYaml file: "input_template.yaml"
                             echo "file1" + file1 
                              name = file1['app']['name']
                        
                            
                            
                              }
     }

}
      stage("Reading attribute from yaml")
   {
      steps{
      
        echo "${name}"
      
     
      }
   }
}
}


