pipeline{
    agent any
    stages {
        stage('Build project'){
            steps{
                echo 'dotnet build'
            }
        }
        stage('Run tests'){
            steps{
                echo 'dotnet test'
            }
        }
    }
}