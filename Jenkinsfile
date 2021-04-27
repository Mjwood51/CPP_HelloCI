//Commit before test

//Here is another revision

pipeline {
    agent { docker { image 'cpphelloci:latest2'} }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World" '
                sh ''' 
                    cpp --version
                    echo "Multiline steps work too"   
                 '''
                docker.image('cpphelloci:latest2').withRun("-p 3000:3000")
            }
        }
    }
}

