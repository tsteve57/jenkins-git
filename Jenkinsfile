pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 8"'
                sh '''
                    echo "Multiline shell steps works too 8"
                    ls -lah
                '''
            }
        }
    }
}


