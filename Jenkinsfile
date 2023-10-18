pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 6"'
                sh '''
                    echo "Multiline shell steps works too 6"
                    ls -lah
                '''
            }
        }
    }
}


