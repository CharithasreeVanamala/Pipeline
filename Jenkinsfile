pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'echo Hello World'
                bat 'javac basic.java'
                bat 'java basic'
            }
        }
    }
}
