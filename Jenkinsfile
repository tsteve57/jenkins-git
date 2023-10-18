pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 3"'
                sh '''
                    echo "Multiline shell steps works too 3"
                    ls -lah
                '''
            }
        }
    }
}


