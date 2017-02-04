
     stage 'Stage 1'
     parallel (
        "stream 1" : { 
  
                               sh "date"                                                       
                               sh "sleep 60s" 
                               sh "echo hstream1"
                               sh "date"                                                       
                           
                       },
        "stream 2" : { 
                        
                               sh "date"                                                       
                               sh "echo hello2"
                               sh "sleep 30s" 
                               sh "date"                                                       
                          
                       }
          )
     
      stage 'Stage 2'
     parallel (
        "stream 3" : { 
                         node { 
                               sh "date"                                                       
                               sh "sleep 60s" 
                               sh "echo hstream3"
                               sh "date"                                                       
                           } 
                       },
        "stream 4" : { 
                         node { 
                               sh "date"                                                       
                               sh "echo hello4"
                               sh "sleep 30s" 
                               sh "date"                                                       
                           } 
                       }
          )
 
