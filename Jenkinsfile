pipeline{
    agent any
    stages {
        stage ('build'){
            steps{
                script{
                    sh """
                        echo "this is build"
                    """
                }
            }
        }
        stage ('test'){
            steps{
                script{
                    sh """
                        echo "this is test stage"
                    """    
                }
            }
        }
        stage('deploy'){
            steps{
                sciprt{
                    sh """
                        echo "this is deploy stage"
                    """
                }
            }
        }
    }
}