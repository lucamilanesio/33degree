pipeline {
    agent { label 'bazel-chrome-latest'}

    stages {
        stage('Build') {
            steps {
                echo 'Environment (it should be private change) '
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