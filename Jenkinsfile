pipeline {
    agent any

    stages {
    
        
         stage('java file ') {
            steps {
            sh "touch cloud.java"
            }
        }
         stage('java execution') {
            steps {
        
            sh "java cloud.java"
            }
        }
         stage('create') {
            steps {
           sh " touch test.py"
            }
        }
         stage('add') {
            steps {
           sh  "echo 'a=90'> test.py"
            }
        }
    }
}
