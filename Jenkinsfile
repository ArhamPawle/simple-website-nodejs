pipeline {
    agent any
    tools { nodejs "node" }
    stages {
        stage('Hello World') {
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
