pipeline {
    agent {
        docker {
            image 'okteto/maven'
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
