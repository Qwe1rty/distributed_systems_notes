# Distributed Systems Notes

**Currently a work in progress!!**

This is my personal collection of links and notes taken while trying to learn about distributed systems.

The structure of these notes is a various mix of paraphrasing/outlines/copying from the resources listed below,
depending on what I felt helped me learn the material the best.

In each folder you'll find the PDF notes, a README giving an outline of the included topics, and individual
JPG images for each page.


## Textbooks 
* Distributed Systems _by Maarten van Steen and Andrew S. Tanenbaum_: <https://www.distributed-systems.net/index.php/books/distributed-systems-3rd-edition-2017/>. _Used by the University of Waterloo's ECE454 [Distributed Computing] course_
* Distributed Algorithms _by Nancy A. Lynch_: <https://learning.oreilly.com/library/view/distributed-algorithms/9781558603486/>
* Computer and Network Organization _by Maarten van Steen and Hank Sips_: <https://www.distributed-systems.net/index.php/books/computer-and-network-organization/>
* Designing Data-Intensive Applications _by Martin Kleppman_: <http://dataintensive.net/>
* Distributed Systems for Fun and Profit _by unknown_: <http://book.mixu.net/distsys/single-page.html>


## Courses
* University of Waterloo's CS454 [Distributed Systems] notes compilation by unknown: <https://paper.dropbox.com/doc/CS-454-Review-Notes-and-Resources-Eb3bsXllcjwyDZrTXMvUM>
* University of Waterloo's CS451 [Data-Intensive Distributed Computing] Winter 2019 resources: <https://roegiest.com/bigdata-2019w/syllabus.html>
* University of Illinois' CS425 [Distributed Systems] Fall 2016 resources: <https://courses.engr.illinois.edu/cs425/fa2016/lectures.html>
  * Video series: <https://www.youtube.com/playlist?list=PLFd87qVsaLhOkTLvfp6MC94iFa_1c9wrU>
* University of Waterloo's ECE358 [Computer Networks] Winter 2016 resources: <https://ece.uwaterloo.ca/~m59wang/ECE358/lectures.html>
* University of Waterloo's CS346 [Networks and Distributed Computer Systems] <https://cs.uwaterloo.ca/~rtholmes/teaching/2011winter/cs436/index.html>
  * Official Coursera series: <https://www.coursera.org/learn/cloud-computing-2#syllabus>
  * Video series: <https://www.youtube.com/playlist?list=PLawkBQ15NDEkDJ5IyLIJUTZ1rRM9YQq6N>
* <http://alvaro-videla.com/2015/12/learning-about-distributed-systems.html>


## Academic Papers Hubs
* <https://dancres.github.io/Pages/>
* <http://book.mixu.net/distsys/single-page.html> (near the bottom)
* <http://dsrg.pdos.csail.mit.edu/papers/>


## Other Resource Hubs
* <https://github.com/binhnguyennus/awesome-scalability>
* <https://github.com/onurakpolat/awesome-bigdata>
* <https://github.com/mfornos/awesome-microservices>
* Suggested resources for networking and distributed systems (and other stuff too) <https://teachyourselfcs.com/>


## Introductory Articles
* <http://www.hpcs.cs.tsukuba.ac.jp/~tatebe/lecture/h23/dsys/dsd-tutorial.html>
* <https://www.freecodecamp.org/news/a-thorough-introduction-to-distributed-systems-3b91562c9b3c/>
* <http://alvaro-videla.com/2015/12/learning-about-distributed-systems.html>
* <https://www.the-paper-trail.org/post/2014-08-09-distributed-systems-theory-for-the-distributed-systems-engineer/>
* <https://medium.com/@thehonourablejeffrey/4a-the-beginning-of-the-end-b9c46537b1c5>
* <https://medium.com/baseds/many-nodes-one-distributed-system-9921f85205c4>
* Overview of distributed computing concepts: <http://alvaro-videla.com/2015/12/learning-about-distributed-systems.html>


## Networking
* Networking videos by Sunny Learning: <https://m.youtube.com/user/sunnylearning/playlists>
* Networking tutorial series by Ben Eater: <https://m.youtube.com/playlist?list=PLowKtXNTBypH19whXTVoG3oKSuOcw_XeW>
##### I/O Handling
* `epoll`, and OS I/O handling: <https://stackoverflow.com/questions/47369971/making-a-http-api-server-asynchronous-with-future-how-does-it-make-it-non-block>

## Design
* <https://www.slideshare.net/mobile/DilumBandara/02-topologies-of-distributed-systems>
* <https://www.slideshare.net/datamantra/building-distributed-systems-from-scratch-part-1>
* <https://www.slideshare.net/datamantra/building-distributed-processing-system-from-scratch-part-2>
* <https://www.slideshare.net/datamantra/evolution-of-apache-spark>


## Coordination
##### Synchronization
* <https://www.quora.com/What-is-synchronous-and-asynchrounous-in-distributed-systems>
##### Clock and Logical Ordering
* Clock synchronization: <https://www.cs.rutgers.edu/~pxk/rutgers/notes/content/09-clock-synchronization-slides-6up.pdf>
* Uses for causality/vector clocks: <http://www.bailis.org/blog/causality-is-expensive-and-what-to-do-about-it/>
* See Maarten van Steen's textbook and the University of Illinois' CS425 resources 
##### Leader Election
* Bully Algorithm network optimization: <https://www.researchgate.net/publication/224568576_A_New_Approach_For_Election_Algorithm_in_Distributed_Systems>
* Explanation of why the Bully Algorithm isn't enough: <https://stackoverflow.com/questions/27558708/whats-the-benefit-of-advanced-master-election-algorithms-over-bully-algorithm>


## Communication Protocols
* <http://csis.pace.edu/~marchese/CS865/Lectures/Chap4/Chapter4.htm>
##### Multicast
* <http://www.tldp.org/HOWTO/Multicast-HOWTO-2.html>
* Explanation of multicast IPs: <http://www.steves-internet-guide.com/introduction-multicasting/>
##### Gossip Protocols
* Full discussion of gossip (including strengths and weaknesses, different types, etc.): <https://managementfromscratch.wordpress.com/2016/04/01/introduction-to-gossip/>
* <http://disi.unitn.it/~montreso/ds/papers/montresor17.pdf>
* Gossip for failure detection, and messaging: <http://highscalability.com/blog/2011/11/14/using-gossip-protocols-for-failure-detection-monitoring-mess.html>
* Gossip performance analysis: <http://phdopen.mimuw.edu.pl/lato08/notes-1.pdf>
##### Gossip Usage
* Explores gossip practices and nuances: <https://ayende.com/blog/169474/gossip-much-use-cases-and-bad-practices-for-gossip-protocols>
* Explains various use cases: <https://www.quora.com/What-is-a-Gossip-protocol>
* Explains usage and role in Cassandra: 
  * <https://stackoverflow.com/questions/29039290/what-is-the-use-of-gossip-protocol-in-apache-cassandra>
  * <https://stackoverflow.com/questions/28127182/data-transmission-between-nodes-and-client-cassandra>
* Process bootstrapping and discovery: <https://docs.datastax.com/en/archived/cassandra/3.0/cassandra/architecture/archGossipAbout.html>
* Anti-entropy process: <https://medium.com/@ifesdjeen/database-papers-anti-entropy-without-merkle-trees-deletes-without-tombstones-a47d2b1608f3>  


## Replication
* Synchronous replication pitfalls: <http://rhaas.blogspot.com/2019/09/synchronous-replication-is-trap.html?m=1>
* Chain replication explanation: <http://dsrg.pdos.csail.mit.edu/2013/08/08/chain-replication/>
* Chain replication by Robbert van Renesse and Fred B. Schneider, 2004: <http://static.usenix.org/legacy/events/osdi04/tech/full_papers/renesse/renesse.pdf>


## Consistency
* Consistency model hierarchy and analysis of popular DBs: <https://jepsen.io/consistency>
##### Single-Node Transactions
* Transactions and concurrency patterns: <https://www.youtube.com/watch?v=onYjxRcToto>
* MVCC explanation: <https://www.youtube.com/watch?v=sxabCqWsFHg>


## Consensus
* Consensus concepts: <https://medium.com/s/story/lets-take-a-crack-at-understanding-distributed-consensus-dad23d0dc95>
* Paxos explanation: <http://lamport.azurewebsites.net/pubs/paxos-simple.pdf>
* Raft interactive visualization: <https://raft.github.io/>
* Raft walkthrough: <http://thesecretlivesofdata.com/raft/>


## Distributed Storage
* <http://www.cs.nuim.ie/~dkelly/CS402-06/Distributed%20File%20Systems.htm>
##### Relational
* <https://blog.sqlauthority.com/2014/10/06/mysql-how-to-create-a-distributed-relational-sql-database/amp/>
* Relational database series: <https://www.youtube.com/playlist?list=PL_c9BZzLwBRK0Pc28IdvPQizD2mJlgoID>
* SQLite file IO specification: <https://www.sqlite.org/fileio.html#tocentry_132>
* SQLite file format specification: <https://www.sqlite.org/fileformat.html>* SQLite File format specification: <https://www.sqlite.org/fileformat.html>* SQLite File format specification: <https://www.sqlite.org/fileformat.html>* SQLite File format specification: <https://www.sqlite.org/fileformat.html>* SQLite File format specification: <https://www.sqlite.org/fileformat.html>* SQLite File format specification: <https://www.sqlite.org/fileformat.html>* SQLite File format specification: <https://www.sqlite.org/fileformat.html>* SQLite File format specification: <https://www.sqlite.org/fileformat.html>
##### Hash Tables
* Chord algorithm paper: <https://pdos.csail.mit.edu/papers/ton:chord/paper-ton.pdf>
* <https://medium.com/techlog/chord-building-a-dht-distributed-hash-table-in-golang-67c3ce17417b>
* <https://hackernoon.com/consistent-hashing-with-bounded-loads-using-a-red-black-tree-b5aaf0d8540f?source=post_page>
##### Dynamo
* Original paper: <https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf>
* Dynamo overview: <https://priyankvex.wordpress.com/2019/10/05/trying-to-wrap-my-head-around-the-dynamo-storage-system-a-deep-dive/>
* Dynamo walkthrough: <https://www.dynamodbguide.com/the-dynamo-paper/>


## Microservices
* <https://microservices.io>
##### Design
* Synchronous vs. asynchronous design: <https://dzone.com/articles/patterns-for-microservices-sync-vs-async>
* CQRS breakdown: <https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs>
##### Event Sourcing
* Event sourcing explanation: <https://microservices.io/patterns/data/event-sourcing.html>
* Vector clock timestamping: <https://stackoverflow.com/questions/41082938/event-sourcing-microservices-how-to-manage-timestamp>


## Encoding
##### B-Trees
* Introduction to B-Trees: <https://dzone.com/articles/database-btree-indexing-in-sqlite>
* SQLite B-Tree specification: <https://sqlite.org/src4/doc/trunk/www/bt.wiki>
* SQLite B-Tree interior page explanation: <https://stackoverflow.com/questions/54546990/in-sqlite-what-is-the-meaning-of-value-of-the-table-b-tree-interior-cells-when>
* SQLite search mechanics explanation: <https://jvns.ca/blog/2014/10/02/how-does-sqlite-work-part-2-btrees/>


## Tutorials
* <https://dzone.com/articles/creating-a-distributed-system-in-300-lines-with-me>
* <https://jack-vanlightly.com/blog/2019/2/1/building-a-simple-distributed-system-the-implementation>
