pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 9"'
                sh '''
                    echo "Multiline shell steps works too 9"
                    ls -lah
                '''
            }
        }
    }
}


