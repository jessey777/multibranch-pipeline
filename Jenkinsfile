pipeline{
    agent any
      stages{
        stage('build') {
          steps{
           echo "hello world"
          }
       }
    }
 }
    stage('dev') {
      when {
        branch "dev"
       }
       steps{
          sh  "cat Jenkinsfile"
       }
    }
    stage('prod') {
     when{
       branch "prod"
     }
      steps{
       echo "run only prod"
       }
     }
    }
   }


