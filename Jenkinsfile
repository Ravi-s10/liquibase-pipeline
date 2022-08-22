def yamlfile
pipeline {
  agent any
  stages{
      stage("Read File") {
      steps{
        script{
          yamlfile= readYaml file: "input_template.yaml
          echo "yamlfile: " + yamlfile
          echo yamlfile['app'['id']
                    }
      }
    }
  }
}
