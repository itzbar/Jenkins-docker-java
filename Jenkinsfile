pipeline {
    agent {
        docker {
            image '... your java and maven image ...'
        }
    }
    stages {
        stage('compile') {
            steps {
                sh 'mvn compile'
            }
        }
    }
}
