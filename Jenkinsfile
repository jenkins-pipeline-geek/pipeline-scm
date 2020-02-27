pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Maven Building..'
            }
        }
        stage('Static-analysis') {
            steps {
                echo 'Sonar-cube validating..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
