def yamlInput
pipeline {
  agent any 
  stages{
      stage("Read File")
    {
      steps{
        script{
          yamlInput = readYaml file: "${WORKSPACE}/input_template.yaml"
          echo "yamlfile: " + yamlInput
          echo yamlInput['app'['id']
                   
                  
          
          
        }
      }
    }
  }
}
