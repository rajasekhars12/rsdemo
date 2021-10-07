
pipeline{
    agent {label 'Node1':'Node2'}
    stages{
        stage("test stage "){
            steps{
                echo "test stage was success"
            }
        }
        stage("code scan stage"){
            steps{
                echo "scan stage was success"
            }
        }
        stage("Build image"){
            steps{
                echo "image was created successfully"
            }
        }
        stage("push image to docker hub"){
            steps{
                echo "image was pushed to dockerhub successfully"
            }
        }

    }
    
}    
