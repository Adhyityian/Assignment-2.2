# Assignment-2.2
1.HDFS
The Hadoop Distributed File System (HDFS) is the primary storage system used by Hadoop applications.

HDFS is a distributed file system that provides high-performance access to data across Hadoop clusters. Like other Hadoop-related technologies, HDFS has become a key tool for managing pools of big data and supporting big data analytics applications.
Because HDFS typically is deployed on low-cost commodity hardware, server failures are common. The file system is designed to be highly fault-tolerant, however, by facilitating the rapid transfer of data between compute nodes and enabling Hadoop systems to continue running if a node fails. That decreases the risk of catastrophic failure, even in the event that numerous nodes fail.

2.Hadoop Cluster
Hadoop clusters are known for boosting the speed of data analysis applications. They also are highly scalable: If a cluster's processing power is overwhelmed by growing volumes of data, additional cluster nodes can be added to increase throughput. Hadoop clusters also are highly resistant to failure because each piece of data is copied onto other cluster nodes, which ensures that the data is not lost if one node fails.
Hadoop clusters are comprised of three different node types: master nodes, worker nodes, and client nodes. Understanding the different node types will help you plan your cluster, and configure the appropriate number and type of nodes when creating a cluster.
Client nodes have Hadoop installed with all the cluster settings, but are neither master or worker nodes. Instead, the client node loads data into the cluster, submits MapReduce jobs describing how that data should be processed, and then retrieves or views the results of the job when processing is finished.

3.HDFS blocks
• A Hard Disk has concentric circles which form
tracks.
• One file can contain many blocks. These blocks in a local file system are nearly 512 bytes and are
not necessarily continuous.
• For HDFS, since it is designed for large files, the block size is 128 MB by default. Moreover, it gets blocks of local file system contiguously to minimise the head seek time.
