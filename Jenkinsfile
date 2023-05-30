pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                sh 'npm -v'
                sh 'nvm -v'
                sh 'dotnet --version'
                echo "====++++executing Build++++===="
            }
        }
    }
}
