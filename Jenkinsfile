pipeline {
    agent any
    stages {
        stage('Checkout!') {
            steps {
                git branch: 'main',
                    credentialsId: 'github-access-token',
                    url: 'https://github.com/boh001/jenkins_tutorial.git'
            }
        }
    }
}