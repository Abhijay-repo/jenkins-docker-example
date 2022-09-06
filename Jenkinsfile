pipeline{
    agent any
    stages{
        stage ('Deploy')
        {
            steps{
                script{
                       sh "npm install"
                       sh "npm build"
                       sh "npm run start"
                   }
                
                }
            
                
            
        }
        
    }
}
