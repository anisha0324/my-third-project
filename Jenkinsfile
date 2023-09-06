pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'aws cloudformation create-stack --stack-name my-second-ec2-stack --template-body file://${WORKSPACE}/ec2.yaml'
            }
        }
    }
}