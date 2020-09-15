pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name mybycket1 --template-body file://cfn-deploy-to-s3 --region 'us-east-1'"
              }
             }
            }
            }
