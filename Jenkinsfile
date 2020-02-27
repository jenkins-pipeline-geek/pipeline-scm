pipeline {
    agent any

    stages {
        stage('Build from feature branch') {
            steps {
                echo "Branch: ${BRANCH_NAME}"
                echo 'Maven Building..'
            }
        }
        stage('Static-analysis from feature branch') {
            steps {
                echo 'Sonar-cube validating..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing from feature branch'
            }
        }
        stage('Deploy from feature branch') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
