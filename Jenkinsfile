pipeline { 
  
  agent{
    node{
      label 'slave'
    }
  }

   stages {
     
     stage('install dependencies'){
         steps{
            sh 'echo "Hello This is dev branch" '
         }
   }
            
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
