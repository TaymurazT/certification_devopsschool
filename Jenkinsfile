pipeline {
    agent {
        label "main"
    }
    tools {
        terraform 'Terra'
    }
    stages{
        stage('Terraform Init'){
            steps{
                dir('/home/allon/certification_devopsschool/'){
                sh 'terraform init'
                }
            }
        }
        stage('Terraform Apply'){
            steps{
                dir('/home/allon/certification_devopsschool/'){
                sh 'terraform apply --auto-approve'
                }
            }
        }

    }
}