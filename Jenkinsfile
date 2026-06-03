pipeline{
    agent any
    stages{
        stage('Clone') {
            steps{
                echo 'cloning repo'
            }
        }
        stage('Build') {
            steps{
                sh 'npm run build'
            }
        }
        stage('Test') {
            steps{
                sh 'npm run test'
            }
        }
    }
}