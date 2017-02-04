parallel (
    "stream 1" : { 
                     node { 
                           "echo 'new Date()'"       
                           sh "sleep 20s" 
                           sh "echo hstream1"
                       } 
                   },
    "stream 2" : { 
                     node { 
                           "echo 'new Date()'"       
                           sh "echo hello2"
                           sh "date"                                                       
                       } 
                   }
          )
