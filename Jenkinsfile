pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                script{
                    sh 'terraform fmt'
                    sh 'terraform validate'
                    }
                }
            }
        }
    }
}