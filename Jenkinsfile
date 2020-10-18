pipeline{
    agent { label 'master'}
    stages{
        stage('unitest'){
            steps{
                sh 'mvn test'
            }
        }
        stage('Build'){
            steps{
                sh 'mvn package'
            }
        }
    }
}