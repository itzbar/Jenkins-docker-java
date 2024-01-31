pipeline {
    agent {
        docker {
            image 'maven'
            args '-u root'
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
