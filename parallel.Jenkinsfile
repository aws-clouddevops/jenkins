pipeline {
    agent any
    stages {
        stage('Parallel'){
            parallel {
                stage('one') {
                    steps {
                        echo "sleep 30"
                   }
                }
                stage('Two') {
                    steps {
                        echo "sleep 30"
                    }
                }
            }
        }
    }
    post {
        unstable {
            cleamWs()
        }
    }
}