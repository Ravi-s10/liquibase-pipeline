def yamlfile


pipeline {

agent any

stages{

stage("Build"){
steps{
script{
   echo "echo"
           yamlfile= readYaml file: "input_template.yaml
          echo "yamlfile: " + yamlfile
          echo yamlfile['app'['id']
  
}
}
}
}
}


