def file1
def app
def name
def email
def region1
def region2
def envprops

                        



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
                              regions1 = file1['app']['region'][0]
                               regions2 = file1['app']['region'][01]
                              envprops = file1['env_prop']['uat']['skip']
                        env_name = file1['env_prop']

                        
                            
                            
                              }
     }

}
      stage("Reading attribute from yaml")
   {
      steps{
      
        echo "${name}"
        echo "${email}"
        echo "${regions1}"
        echo "${envprops}"
        echo "${env_name}"
     
      
     
      }
   }

  
       stage("Reading attribute new from yaml")
   {
      steps{
      
   echo "Hello"
      
     
      }
   }

}
  
  
  
  }


