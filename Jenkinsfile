def builderImage
def productionImage
def ACCOUNT_REGISTRY_PREFIX
def GIT_COMMIT_HASH

pipeline {
    agent any
    stages {
        stage('Checkout Source Code and Logging Into Registry') {
            steps {
                echo 'Logging Into the Private ECR Registry'
            }
        }

        stage('Make A Builder Image') {
            steps {
                echo 'Starting to build the project builder docker image'
            }
        }

        stage('Unit Tests') {
            steps {
                echo 'running unit tests in the builder image.'
            }
        }

        stage('Build Production Image') {
            steps {
                echo 'Starting to build docker image'
                }
            }
        }
     
}
