##History
I have tried to write a blog post (http://seriousprog.blogspot.com/2013/01/some-need-to-be-read-papers-in-cloud.html) about the reading list for researchers in distributed computing and cloud computing. However, this post can not be visited in China, so i decided to write here with exteded information like the brief introduction of the papers or some reviews. If you have any suggestions, please email me or comment below, i will keep improving this post.

##Basic Theory
[Chubby] Burrows, Mike. "The Chubby lock service for loosely-coupled distributed systems." Proceedings of the 7th symposium on Operating systems design and implementation. USENIX Association, 2006. http://www.usenix.org/event/osdi06/tech/full_papers/burrows/burrows_html/

Armbrust, M.; Fox, A.; Griffith, R.; Joseph, A.; Katz, R.; Konwinski, A.; Lee, G.; Patterson, D.; Rabkin, A.; Stoica, I. & others "A view of cloud computing" Communications of the ACM, ACM, 2010, 53, 50-58. http://x-integrate.de/x-in-cms.nsf/id/DE_Von_Regenmachern_und_Wolkenbruechen_-_Impact_2009_Nachlese/$file/abovetheclouds.pdf

##Programming Model
Abadi, D. J., Ahmad, Y., Balazinska, M., Cetintemel, U., Cherniack, M., Hwang, J. H., ... & Zdonik, S. (2005, January). The design of the borealis stream processing engine. CIDR. http://www.cs.harvard.edu/~mdw/course/cs260r/papers/borealis-cidr05.pdf

Dean, Jeffrey, and Sanjay Ghemawat. "MapReduce: simplified data processing on large clusters." Communications of the ACM 51.1 (2008): 107-113. http://fastandfuriousdecisiontree.googlecode.com/svn-history/r474/trunk/DIVERS/mapReduceByGoogle.pdf

Neumeyer, L., Robbins, B., Nair, A., & Kesari, A. (2010, December). S4: Distributed stream computing platform. In Data Mining Workshops (ICDMW), 2010 IEEE International Conference on (pp. 170-177). IEEE. http://www.4lunas.org/pub/2010-s4.pdf

Zaharia, M.; Chowdhury, M.; Franklin, M.; Shenker, S. & Stoica, I. "Spark: cluster computing with working sets" Proceedings of the 2nd USENIX conference on Hot topics in cloud computing, 2010, 10-10   http://www.usenix.org/event/hotcloud10/tech/full_papers/Zaharia.pdf

Zaharia, Matei, et al. "Discretized streams: an efficient and fault-tolerant model for stream processing on large clusters." Proceedings of the 4th USENIX conference on Hot Topics in Cloud Ccomputing. USENIX Association, 2012. http://www.cs.berkeley.edu/~matei/papers/2012/hotcloud_spark_streaming.pdf

Gunda, Pradeep Kumar, et al. "Nectar: automatic management of data and computation in datacenters." Proceedings of the 9th USENIX conference on Operating systems design and implementation. USENIX Association, 2010. http://static.usenix.org/events/osdi10/tech/full_papers/Gunda.pdf

Peng, Daniel, and Frank Dabek. "Large-scale incremental processing using distributed transactions and notifications." Proceedings of the 9th USENIX conference on Operating systems design and implementation. USENIX Association, 2010. http://www.usenix.org/event/osdi10/tech/full_papers/Peng.pdf

Low, Yucheng, et al. "Distributed GraphLab: a framework for machine learning and data mining in the cloud." Proceedings of the VLDB Endowment 5.8 (2012): 716-727. http://arxiv.org/pdf/1204.6078

Mitchell, Christopher, Russell Power, and Jinyang Li. "Oolong: Programming Asynchronous Distributed Applications with Triggers." Proc. SOSP. 2011. http://sigops.org/sosp/sosp11/posters/summaries/sosp11-final6.pdf

Mitchell, Christopher, Russell Power, and Jinyang Li. "Oolong: asynchronous distributed applications made easy." Proceedings of the Asia-Pacific Workshop on Systems. ACM, 2012. https://apsys2012.kaist.ac.kr/media/papers/apsys2012-final28.pdf

Power, Russell, and Jinyang Li. "Piccolo: building fast, distributed programs with partitioned tables." Proceedings of the 9th USENIX conference on Operating systems design and implementation. USENIX Association, 2010. http://www.usenix.org/event/osdi10/tech/full_papers/Power.pdf

McSherry, Frank, et al. "Differential dataflow." Conference on Innovative Data Systems Research (CIDR). 2013. http://research.microsoft.com/pubs/176693/differentialdataflow.pdf

###Improvement on Existed Models
Zaharia, M.; Konwinski, A.; Joseph, A.; Katz, R. & Stoica, I. "Improving mapreduce performance in heterogeneous environments" Proceedings of the 8th USENIX conference on Operating systems design and implementation, 2008, 29-42. http://www.usenix.org/event/osdi08/tech/full_papers/zaharia/zaharia_html/

Yang, Hung-chih, et al. "Map-reduce-merge: simplified relational data processing on large clusters." Proceedings of the 2007 ACM SIGMOD international conference on Management of data. ACM, 2007. http://www.cs.duke.edu/courses/cps399.28/current/papers/sigmod07-YangDasdanEtAl-map_reduce_merge.pdf

Bu, Yingyi, et al. "HaLoop: Efficient iterative data processing on large clusters." Proceedings of the VLDB Endowment 3.1-2 (2010): 285-296. http://vldb2010.org/proceedings/files/papers/R25.pdf

Borthakur, Dhruba, et al. "Apache Hadoop goes realtime at Facebook."Proceedings of the 2011 international conference on Management of data. ACM, 2011. http://oss.csie.fju.edu.tw/~tzu98/Apache%20Hadoop%20Goes%20Realtime%20at%20Facebook.pdf

Ekanayake, Jaliya, et al. "Twister: a runtime for iterative mapreduce."Proceedings of the 19th ACM International Symposium on High Performance Distributed Computing. ACM, 2010. http://www.iterativemapreduce.org/hpdc-camera-ready-submission.pdf

Zhang, Yanfeng, et al. "Priter: a distributed framework for prioritized iterative computations." Proceedings of the 2nd ACM Symposium on Cloud Computing. ACM, 2011. http://rio.ecs.umass.edu/mnilpub/papers/socc11-zhang.pdf

Bhatotia, Pramod, et al. "Incoop: MapReduce for incremental computations."Proceedings of the 2nd ACM Symposium on Cloud Computing. ACM, 2011. https://www.systems.ethz.ch/education/spring-2012/hotDMS/papers/incoop-socc11.pdf


##Storage
Ghemawat, Sanjay, Howard Gobioff, and Shun-Tak Leung. "The Google file system." ACM SIGOPS Operating Systems Review. Vol. 37. No. 5. ACM, 2003. ftp://121.9.13.178/PPP/ppt-hadoop/The.Google.File.System.pdf

Chang, Fay, et al. "Bigtable: A distributed storage system for structured data."ACM Transactions on Computer Systems (TOCS) 26.2 (2008): 4. http://static.usenix.org/event/osdi06/tech/chang/chang_html/

DeCandia, G., Hastorun, D., Jampani, M., Kakulapati, G., Lakshman, A., Pilchin, A., ... & Vogels, W. (2007, October). Dynamo: amazon's highly available key-value store. In ACM SIGOPS Operating Systems Review (Vol. 41, No. 6, pp. 205-220). ACM. http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/decandia07dynamo.pdf

McKusick, Marshall Kirk, and Sean Quinlan. "Gfs: Evolution on fast-forward."ACM Queue 7.7 (2009): 10-20. http://queue.acm.org/detail.cfm?id=1594206

Weil, Sage A., et al. "Ceph: A scalable, high-performance distributed file system." Proceedings of the 7th Symposium on Operating Systems Design and Implementation (OSDI). 2006. https://www.usenix.org/legacyurl/osdi-06-paper-4

Lakshman, Avinash, and Prashant Malik. "Cassandra—A decentralized structured storage system." Operating systems review 44.2 (2010): 35. http://www.cs.cornell.edu/Projects/ladis2009/papers/Lakshman-ladis2009.PDF

Baker, J., Bond, C., Corbett, J. C., Furman, J. J., Khorlin, A., Larson, J., ... & Yushprakh, V. (2011, January). Megastore: Providing scalable, highly available storage for interactive services. In Proc. of CIDR (pp. 223-234). http://pdos.csail.mit.edu/6.824-2012/papers/jbaker-megastore.pdf

Ousterhout, John, Parag Agrawal, David Erickson, Christos Kozyrakis, Jacob Leverich, David Mazières, Subhasish Mitra et al. "The case for ramcloud."Communications of the ACM 54, no. 7 (2011): 121-130. http://ilpubs.stanford.edu:8090/942/1/ramcloud.pdf

Ongaro, Diego, Stephen M. Rumble, Ryan Stutsman, John Ousterhout, and Mendel Rosenblum. "Fast crash recovery in RAMCloud." In Proceedings of the Twenty-Third ACM Symposium on Operating Systems Principles, pp. 29-41. ACM, 2011. http://www.cs.columbia.edu/~junfeng/11fa-e6121/papers/ramcloud-recovery.pdf

Lloyd, Wyatt, et al. "Don't settle for eventual: scalable causal consistency for wide-area storage with COPS." Proceedings of the Twenty-Third ACM Symposium on Operating Systems Principles. ACM, 2011. http://www-users.cselabs.umn.edu/classes/Fall-2012/csci8980-2/papers/cops.pdf

Stonebraker, M., Abadi, D. J., Batkin, A., Chen, X., Cherniack, M., Ferreira, M., ... & Zdonik, S. (2005, August). C-store: a column-oriented DBMS. In Proceedings of the 31st international conference on Very large data bases (pp. 553-564). VLDB Endowment. http://people.csail.mit.edu/tdanford/6830papers/stonebraker-cstore.pdf

Hall, A., Bachmann, O., Büssow, R., Gănceanu, S., & Nunkesser, M. (2012). Processing a trillion cells per mouse click. Proceedings of the VLDB Endowment, 5(11), 1436-1446. http://vldb.org/pvldb/vol5/p1436_alexanderhall_vldb2012.pdf

Abadi, Daniel J., Samuel R. Madden, and Nabil Hachem. "Column-Stores vs. Row-Stores: How different are they really?." Proceedings of the 2008 ACM SIGMOD international conference on Management of data. ACM, 2008. http://www.courses.fas.harvard.edu/~cs265/papers/abadi-2008.pdf

##Scheduler
Zaharia, M.; Borthakur, D.; Sen Sarma, J.; Elmeleegy, K.; Shenker, S. & Stoica, I. "Delay scheduling: a simple technique for achieving locality and fairness in cluster scheduling" Proceedings of the 5th European conference on Computer systems, 2010, 265-278.  http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.212.1524&rep=rep1&type=pdf

Hindman, Benjamin, et al. "Mesos: A platform for fine-grained resource sharing in the data center." Proceedings of the 8th USENIX conference on Networked systems design and implementation. USENIX Association, 2011. http://incubator.apache.org/mesos/papers/nsdi_mesos.pdf

Ghodsi, A., Zaharia, M., Hindman, B., Konwinski, A., Shenker, S., & Stoica, I. (2011, March). Dominant resource fairness: fair allocation of multiple resource types. In USENIX NSDI. http://static.usenix.org/event/nsdi11/tech/full_papers/Ghodsi.pdf

##Systems
Melnik, S., Gubarev, A., Long, J. J., Romer, G., Shivakumar, S., Tolton, M., & Vassilakis, T. (2010). Dremel: interactive analysis of web-scale datasets. Proceedings of the VLDB Endowment, 3(1-2), 330-339. http://static.googleusercontent.com/external_content/untrusted_dlcp/research.google.com/en/us/pubs/archive/36632.pdf

##Cluster Management
##Applications

