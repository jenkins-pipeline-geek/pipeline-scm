pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // echo "Branch: ${BRANCH_NAME}" // This is applicable to Multi-branch pipeline
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
                echo 'Testing from feature branch'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
