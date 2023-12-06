@Library("shared-library") _
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                helloWorld()
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                helloWorld()
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                helloWorld()
            }
        }
    }
}