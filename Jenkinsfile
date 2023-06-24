pipeline {
    agent { label 'bazel-chrome-latest'}

    stages {
        stage('Build') {
            steps {
                echo 'Environment: '
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