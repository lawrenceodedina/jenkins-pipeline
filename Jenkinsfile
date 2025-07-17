pipeline {
    agent any
    stages{
        stage('clone'){
            steps{
                sh 'echo "cloning repository"'
                sh 'uname -r'
            }
        }
        stage('test'){
        steps{
            sh 'echo test'
        }
    }
        stage('create file'){
            steps{
                sh 'touch text-$BUILD_ID'
            }
        }
    }
}