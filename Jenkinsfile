pipeline{
  agent none
  stages{
     stage("Build Master"){
        when{
           tag '2.0'
        }
         steps{
           echo "Building Tag catched in main"
         }
     }     
    
  }
}
