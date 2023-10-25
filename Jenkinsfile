pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 10"'
                sh '''
                    echo "Multiline shell steps works too 10"
                    ls -lah
                '''
            }
        }
    }
}


