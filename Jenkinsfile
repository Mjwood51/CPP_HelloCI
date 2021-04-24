pipeline {
    agent { docker { image 'cpphelloci:latest2' } }
    stages {
        stage('build') {
            steps {
                sh 'cpp --version'
            }
        }
    }
}

