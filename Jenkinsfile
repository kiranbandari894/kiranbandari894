pipeline{
  agent none
  stages{
     stage("Build Master"){
        when{
           buildingTag()
        }
         steps{
           echo "Building Tag catched in main"
         }
     }     
    
  }
}
