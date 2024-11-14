pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                script{
                    sh 'terraform fmt'
                    sh 'terraform validate'
                    sh 'echo hello'

                }
            }
        }
    }
}