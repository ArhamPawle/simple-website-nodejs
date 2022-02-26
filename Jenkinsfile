pipeline {
    agent any
    tools { nodejs "node" }
    stages {
        stage('Hello World Take 2') {
            steps {
                sh "npm install"
            }
        }
        stage('Deploy') {
            steps {
                sh "npm start"
            }
        }
    }
}
