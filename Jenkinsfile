pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2 --template-body file://ec2-cfn-jenkins --region 'us-east-1'"
              }
             }
            }
            }
