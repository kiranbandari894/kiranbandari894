pipeline{
  agent none
  stages{
     stage("Build Master"){
        when{
           tag '1.2'
        }
         steps{
           echo "Building Tag catched in main"
         }
     }     
    
  }
}
