pipeline {
    agent {
        label: 'ANSIBLE'
    }
    stages {
        stage('Parallel'){
            parallel {
                stage('one') {
                    steps {
                        sh "hostname"
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