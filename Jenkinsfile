pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning Repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Project...'
            }
        }

        stage('Show HTML Content') {
            steps {
                bat 'type index.html'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Project...'
            }
        }
    }
}