pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh "docker pull ubuntu"
            }
        }
    }
}
