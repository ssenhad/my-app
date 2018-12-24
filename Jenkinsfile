pipeline {
    agent any 
    stages {
        stage('-----clean-----') { 
            steps {
                bat "mvnn clean"
            }
        }
        stage('-----Test-----') { 
            steps {
                bat "mvn test"
            }
        }
        stage('-----package-----') { 
            steps {
                bat "mvn package"
            }
        }
    }
}
