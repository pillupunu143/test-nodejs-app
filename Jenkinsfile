pipeline { 
  
   agent any

   stages {
     
     stage('install dependenices') { 
        steps { 
           sh 'apt install'
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
