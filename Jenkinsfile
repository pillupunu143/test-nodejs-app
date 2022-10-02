pipeline { 
  
   agent any

   stages {
     
     stage('install dependenices') { 
        steps { 
           sh 'sudo npm install'
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
