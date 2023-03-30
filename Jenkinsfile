pipeline{
    agent any
    stages{
        stage('1-clonecode'){
            steps{
                sh 'whoami'
            }
        }
        stage('2-memorycheck'){
            steps{
                sh 'free -g'
            }
        }
    }
}                