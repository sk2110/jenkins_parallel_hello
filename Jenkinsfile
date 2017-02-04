parallel (
    "stream 1" : { 
                     node { 
                           unstash "binary"                           
                           sh "sleep 20s" 
                           sh "echo hstream1"
                       } 
                   },
    "stream 2" : { 
                     node { 
                           unstash "binary"
                           sh "echo hello2"
                           sh "hashtag fail"                                                       
                       } 
                   }
          )
