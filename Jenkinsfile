pipeline{
    agent{
        docker{
            image 'node:20'
        }
    }
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
