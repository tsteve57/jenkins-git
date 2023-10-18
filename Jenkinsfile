pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 4"'
                sh '''
                    echo "Multiline shell steps works too 4"
                    ls -lah
                '''
            }
        }
    }
}


