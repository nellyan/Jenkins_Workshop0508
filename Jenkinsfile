pipeline {
    agent any

    stages{
        stage("Checkout code") {
            //checkout the repository
            steps{
                git branch: 'main', url: 'https://github.com/nellyan/Jenkins_Workshop0508'
            }
        }
        stage("Setup .Net Core") {
            //install dot net
        }
        stage("Restore dependencies") {
            //install dependencies
        }
        stage("Build") {
            //build
        }
        stage("Run tests") {
            //run tests
        }
    }
}