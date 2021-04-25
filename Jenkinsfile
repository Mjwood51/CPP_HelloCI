//Commit before test

//Here is another revision

pipeline {
    agent { docker { image 'cpphelloci:latest2'} }
    stages {
        stage('build') {
            steps {
                sh 'docker run mjwood51/docker-repo:latest'
                sh 'cpp --version'
            }
        }
    }
}

