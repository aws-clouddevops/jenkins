pipeline {  
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hi') { 
            steps {
                sh '''echo hello
                      echo We are learning jenkins'''
            }
        }
    }
}