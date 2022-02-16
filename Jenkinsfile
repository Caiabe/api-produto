pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.build("produto/api-produto", '-f ./src/Dockerfile ./src') 
                }                
            }    
        }
    }

}