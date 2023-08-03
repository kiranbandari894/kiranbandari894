pipeline{
  agent none
  stages{
     stage("Build" Master"){
        when{
          branch 'main'
        }
         steps{
           echo "Hello Main branch"
         }
     } 
     stage("Build Dev"){
        when{
          branch 'dev'
        }
         steps{
           echo "Hello Development branch"
         }
     }    
    
  }
}
