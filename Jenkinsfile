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
            environment{
                ENV_URL = "stage.google.com"
            }
            steps {
                sh "echo hello"
                sh "echo Environment URL is ${ENV_URL}"
            }
        }
    }
}