pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://s3cfn.json.json --region 'us-west-2'"
              }
             }
            }
            }
