pipeline{
    agent any
    stages{
        stage('buold'){
            stepts{
                script{
                    sh """"
                        echo " this is build stage"
                    """    
                }
            }

        }
        stage('test'){
            script{
                sh """
                    echo " this is test stage"
                   """ 
            }
        }
        stage('deploy'){
            stepts{
                script{
                    sh """
                        echo "thid is depoy stage"
                     """   
                }
            }
        }
    }
}