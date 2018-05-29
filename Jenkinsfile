Jenkinsfile (Declarative Pipeline)
pipeline {
    agent {
        docker { image 'larrybox:friendlyhello' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
