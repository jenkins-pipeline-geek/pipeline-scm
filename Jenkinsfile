pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Branch: $BRANCH_NAME'
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
