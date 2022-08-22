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
                              name = file1['app']['name']
                              email = file1['app']['email']
                              regions = file1['app']['region']
                              envprops = file1['env_prop']['qa']
                        
                            
                            
                              }
     }

}
      stage("Reading attribute from yaml")
   {
      steps{
      
        echo "${name}"
        echo "${email}"
        echo "${regions}"
        echo "${envprops}"
      
     
      }
   }
}
}


