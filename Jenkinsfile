pipeline {
    agent any

    stages {
    
        
         stage('build') {
            steps {
            sh "python3 demo.py"
            }
        }
           stage('install ') {
            steps {
            sh "sudo yum install httpd -y"
            }
        }
        
    }
}
