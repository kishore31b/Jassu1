pipeline{
    agent any 
    
    stages{ 
        stage("checkout-SCM"){
            steps{
                echo "hello jenkins"
            }
        }
        stage("build"){
            steps{
                echo "artifactory created using mvn"
            }
        }
        
        stage("deplyment"){
            steps{
                echo "deploying to tomcat server"
            }
        }
          stage("testing"){
            steps{
                echo "testing the artifcatory stability"
            }
            
        }
        
        stage("artifactory"){
            steps{
                echo "uploading into artfcatory"
            }
            
        }
    }
}
