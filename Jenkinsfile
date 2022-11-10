pipeline {  # Directives
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hi') { # Directives
            steps {
                sh '''echo hello
                      echo We are learning jenkins'''
            }
        }
    }
}