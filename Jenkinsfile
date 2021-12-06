pipeline {
    agent any

    stages {
        stage('V') {
            steps {
                echo 'Hello World'
                sh 'npm -v'
                sh 'node -v'
                sh "yarn -v"
            }
        }
          stage('Stage 2') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
