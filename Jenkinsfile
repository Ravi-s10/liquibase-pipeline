def yamlInput
pipeline {
  agent any
  node {
     yamlInput = readYaml file: "${WORKSPACE}/input_template.yaml"
  }
  stages{
      stage("Read File")
    {
      steps{
        script{
         
          echo "yamlfile: " + yamlInput
          echo yamlInput['app'['id']
                   
                  
          
          
        }
      }
    }
  }
}
