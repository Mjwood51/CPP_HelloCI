//Commit before test

//Here is another revision

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

