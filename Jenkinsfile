pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://1-CFNInit.yaml --region 'ap-southeast-2'"
              }
             }
            }
            }
