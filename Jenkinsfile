pipeline {
    agent {
        docker { image 'friendlyhello' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
