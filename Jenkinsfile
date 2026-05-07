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
            sh "yum install httpd -y"
            }
        }
        
    }
}
