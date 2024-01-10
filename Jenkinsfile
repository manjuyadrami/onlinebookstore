pipeline {  
    agent any  
        stages {  
       	    stage("clone code"){
                steps{
        print "clone"
                }
    }
      stage("maven build"){
          steps{
        print "maven"
          }
    }
      stage("upload artifact"){
          steps{
        print "upload"
          }
    }
    
       stage("deploy to dev"){
           steps{
        print "deploy"
           }
    }
}
}
