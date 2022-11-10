pipeline {  
    agent any

    environment{
        ENV_URL = "pipeline.google.com"
    }

    stages {
        stage('Hello') {
            steps {
                sh "echo ${ENV_URL}"
            }
        }
        stage('Hi') { 
            steps {
                sh "echo hello"
                sh "echo Environment URL is ${ENV_URL}"
            }
        }
    }
}