pipeline {
    agent { label 'bazel-chrome-latest'}

    stages {
        stage('Build') {
            steps {
                echo 'Environment (it should be private and WIP change) '
                sh 'printenv | sort'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing again ..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}