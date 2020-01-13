pipeline{
    agent any 
    
    stages{ 
        stage("checkout-SCM"){
            steps{
                   checkout([$class: 'GitSCM', branches: [[name: '*/master']],
                             doGenerateSubmoduleConfigurations: false,
                             extensions: [], 
                             submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'jenkins',
                             url: 'https://github.com/kishore31b/Jassu1.git']]])
            }
        }
    }
}
