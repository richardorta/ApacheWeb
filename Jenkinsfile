pipeline {
    agent {
        label 'linux'
    }

    environment {
        GRADLE_HOME = tool('gradle-4.6')

    }

    stages {
        stage('clean') {
            steps {
                sh '$JAVA_HOME/bin/javac --version'
            }
        }        
        
    }

}
