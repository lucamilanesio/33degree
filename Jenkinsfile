pipeline {
    agent { label 'bazel-chrome-latest'}

    stages {
        stage('Build') {
            steps {
                sh 'printenv'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}