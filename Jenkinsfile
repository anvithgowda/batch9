pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'java -version'  
            }
        }
        stage('Test') { 
            steps {
                git 'https://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@github.com/anvithgowda/batch9.git' 
            }
        }
        stage('Deploy') { 
            steps {
                sh 'jenkins --version' 
            }
        }
    }
}
