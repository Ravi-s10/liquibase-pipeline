def file1
def app
def name
def email
def region1
def region2
def envprops

                        
def is_skip(){
  
  if (envprops == true)
  println("okayyy")
 
  
}



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
        is_skip()
      
     
      }
   }
}
}


