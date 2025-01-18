pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone-Code') {
            steps {
              git branch: 'main', url: 'https://github.com/ankit-17107/Integrated-Terraform-Infrastructure-Automation-and-DevOps-Pipeline-with-Kubernetes-and-Helm.git'
            }
        }
    }
}

