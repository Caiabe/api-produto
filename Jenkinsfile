pipeline {
    agent any

    stages {
        stage ('Build Image') {
            script {
                dockerapp = docker.build("appproduto/api-produto", '-f' ./src/Dockerfile ./src)
            }
        }
    }
}