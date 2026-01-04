pipeline{
    agent { label 'AGENT-1' }
    stages{
        stage('build'){
            steps{
                script{
                    sh """
                        echo " this is build stage"
                    """    
                }
            }

        }
        stage('test'){
            steps{
                script{
                    sh """
                        echo " this is test stage"
                    """ 
                }
            }
        }
        stage('deploy'){
            steps{
                script{
                    sh """
                        echo "thid is depoy stage"
                     """   
                }
            }
        }
    }
}