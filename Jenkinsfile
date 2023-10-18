pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 5"'
                sh '''
                    echo "Multiline shell steps works too 5"
                    ls -lah
                '''
            }
        }
    }
}


