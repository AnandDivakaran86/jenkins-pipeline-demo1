pipeline {
    agent any 
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello, Maven'
                sh 'git --version'
            }
        }
        stage('Example Test') {
            steps {
                echo 'Hello, JDK'
                sh 'git --version'
            }
        }
    }
}
