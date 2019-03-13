pipeline {
    agent {
        label 'linux'
    }
    
    options {
        disableConcurrentBuilds()
    }

    environment {
        
    }
    
    

    stages {
        stage('build') {
            steps {
                sh 'docker pull httpd'
            }
        }        
        
    }

}
