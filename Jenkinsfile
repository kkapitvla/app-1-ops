pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/kkapitvla/jenkinstest', branch: 'main'
            }
        }
    }
}
