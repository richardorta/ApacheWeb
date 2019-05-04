pipeline {
    agent {
        label 'linux'
    }

    options {
        disableConcurrentBuilds()
    }

    environment {
        DESC="Add more details here."
        
    }

    stages {
        stage('prebuild') {
            steps{
                sh 'env'
            }
        }

      stage('build') {
            steps {
                sh 'docker pull httpd'
            }

        stage('post-build') {
            steps{
                sh 'echo This is the post-stage section.'
            }
        }
    }

}
