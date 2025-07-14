pipeline {
    agent any

    stages {
        stage('Terraform init') {
            steps {
                script {
                    sh "terraform init"
                }
            }
        }
        stage('Terraform plan') {
            steps {
                script {
                    sh "terraform plan"
                    
                }
            }
        }
        stage('Terraform apply and auto approve') {
            steps {
                script {
                    sh "terraform apply -auto-approve"
                }
            }
        }
      
	}
}
	
