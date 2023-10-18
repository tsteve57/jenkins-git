pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 7"'
                sh '''
                    echo "Multiline shell steps works too 7"
                    ls -lah
                '''
            }
        }
    }
}


