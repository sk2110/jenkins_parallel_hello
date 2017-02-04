parallel (
    "stream 1" : { 
                     node { 
                           sh "echo new Date().format( 'yyyyMMdd' )"       
                           sh "sleep 20s" 
                           sh "echo hstream1"
                       } 
                   },
    "stream 2" : { 
                     node { 
                           sh "echo new Date().format( 'yyyyMMdd' )"       
                           sh "echo hello2"
                           sh "date"                                                       
                       } 
                   }
          )
