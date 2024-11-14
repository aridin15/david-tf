pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                script{
                    sh 'echo hello'
                    sh 'terraform fmt'
                    sh 'terraform validate'

                }
            }
        }
    }
}