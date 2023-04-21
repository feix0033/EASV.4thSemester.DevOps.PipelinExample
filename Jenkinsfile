pipeline{
    agent any

    triggers {
        pollSCM("* * * * *")
    }

    stages{

        stage("Build"){

            steps{
                echo "====++++executing Build++++===="
            }
            post{
                always{
                    echo "====++++always++++===="
                }
                success{
                    echo "====++++Build executed successfully++++===="
                }
                failure{
                    echo "====++++Build execution failed++++===="
                }
        
            }
        }

        stage("Test"){
            steps{
                echo "====++++executing Test++++===="
            }
            post{
                always{
                    echo "====++++always++++===="
                }
                success{
                    echo "====++++Test executed successfully++++===="
                }
                failure{
                    echo "====++++Test execution failed++++===="
                }
        
            }
        }
       
        stage("Deliver"){
            steps{
                echo "====++++executing Deliver++++===="
            }
            post{
                always{
                    echo "====++++always++++===="
                }
                success{
                    echo "====++++Deliver executed successfully++++===="
                }
                failure{
                    echo "====++++Deliver execution failed++++===="
                }
        
            }
        }
    }
  
}