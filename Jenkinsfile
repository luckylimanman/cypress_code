pipeline {
    agent any
    tools { nodejs "nodejs_lim"}
    stages {
        stage('Build') {
            steps {
                sh '''
                npm install
                node index.js
                '''
                sh 'echo "Hello World"'
            }
        }
    }
}
