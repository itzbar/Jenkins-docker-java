pipeline {
    agent {
        docker {
            image 'maven'
            arg '--network=host'
        }
    }
    stages {
        stage('compile') {
            steps {
                sh '# mvn clean compile -Dmaven.repo.local=m2'
                sh 'wget google.com'
            }
        }
    }
}
