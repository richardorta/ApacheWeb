pipeline {
    agent {
        label 'linux'
    }

    environment {
        JAVA_HOME = tool('java')

    }

    stages {
        stage('clean') {
            steps {
                sh '$JAVA_HOME/bin/javac --version'
            }
        }        
        
    }

}
