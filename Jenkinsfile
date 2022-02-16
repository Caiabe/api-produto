pipeline {
    agent any

    stages {
        stage ('Build Image') {
            script {
                    dockerapp = docker.build("produto/api-produto:${env.BUILD_ID}", '-f ./src/Dockerfile ./src') 
                }    
        }
    }
}