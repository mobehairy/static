pipeline { 
     agent any 
     stages { 
       stage ('Upload to AWS.') {
             steps { 
                 sh ' echo echo "Hello World"'
                 sh '''
                      echo "Multiline shell steps works too"
                      ls -lah
                 '''
             }
       }
     }
}
