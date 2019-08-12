pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Fuck You World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
