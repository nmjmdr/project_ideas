# Project Ideas:

## raka - raft Kafka
Combine ideas of raft and Kafka to build a topic based message queue
Ref: http://blog.rodeo.io/2016/01/24/kudu-as-a-more-flexible-kafka.html

project spec:
1. kafka like pull-based model

2. http and tcp end points

3. durable storage of messages

4. only once delivery (with unique event ids? (flake id)) (onus on client to determine if it has consumed the event)

5. support for archiving of messages (through raft log archivial)


## raft-max
Brings fault-tolerance to LMAX architecture
Ref: http://stackoverflow.com/questions/23535740/lmax-replicator-design-how-to-support-high-availability

## Distributed Throttler
Probable use of gossip protocol 
(merkel trees to repair? - from aphyr's task engine code?)


Try and adrress what is pointed out as future work here: https://yahooeng.tumblr.com/post/111288877956/cloud-bouncer-distributed-rate-limiting-at-yahoo


http://docs.hcs.ufl.edu/pubs/GEMS2005.pdf


https://cseweb.ucsd.edu/~snoeren/papers/drl-sigcomm07.pdf


http://highscalability.com/blog/2011/11/14/using-gossip-protocols-for-failure-detection-monitoring-mess.html


http://sbrc2010.inf.ufrgs.br/resources/presentations/tutorial/tutorial-montresor.pdf


Use clojure? 

Note to self: more items on google drive keyword "potential ideas"
