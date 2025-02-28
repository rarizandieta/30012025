pipeline {
    agent any

    stages{
        stage('Checkout')
        {
            steps{
                git 'https://github.com/rarizandieta/30012025.git'
            }
        }

        stage('Build')
        {
            steps{
                sh 'echo "Building the app"'
            }
        }

        stage('Test')
        {
            steps{
                sh 'echo "Testing the app"'
            }
        }

        stage('Deploy')
        {
            steps{
                sh 'echo "Deploying the app"'
            }
        }
    }
}