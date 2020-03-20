pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name myteststack --template-body file://1-CFNInit.yaml --parameters ParameterKey=NameOfService,ParameterValue=webservice ParameterKey=KeyName,ParameterValue=eric-keypair --region 'ap-southeast-2'"
              }
             }
            }
            }
