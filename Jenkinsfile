parallel (
    "stream 1" : { 
                     node { 
                           sh "date"                                                       
                           sh "sleep 60s" 
                           sh "echo hstream1"
                           sh "date"                                                       
                       } 
                   },
    "stream 2" : { 
                     node { 
                           sh "date"                                                       
                           sh "echo hello2"
                           sh "sleep 30s" 
                           sh "date"                                                       
                       } 
                   }
          )
