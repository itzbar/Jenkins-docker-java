pipeline {
    agent {
        docker {
            image 'maven'
        }
    }
    stages {
        stage('compile') {
            steps {
                sh 'mvn clean compile -Dmaven.repo.local=m2'
            }
        }
    }
}
