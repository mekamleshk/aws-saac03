- Aurora is a AWS designed database engine officially part of RDS

- Aurora implements a number of radical design changes which offer significant performance and feature improvements over other RDS database engines.

![alt text](image-41.png)

![alt text](image-42.png)

![alt text](image-43.png)

![alt text](image-44.png)

![alt text](image-45.png)

![alt text](image-46.png)

 ![alt text](image-2.png)

 ![alt text](image-3.png)

 ![alt text](image-4.png)

 ![alt text](image-5.png)

 ![alt text](image-6.png)

 ![alt text](image-7.png)

![alt text](image-8.png)

- Aurora global databases are a feature of Aurora Provisioned clusters which allow data to be replicated globally providing significant RPO and RTO improvements for BC and DR planning. Additionally global databases can provide performance improvements for customers .. with data being located closer to them, in a read-only form.

- Replication occurs at the storage layer and is generally ~1second between all AWS regions.

![alt text](image-50.png)

![alt text](image-51.png)

- Multi-master write is a mode of Aurora Provisioned Clusters which allows multiple instances to perform reads and writes at the same time - rather than only one primary instance having write capability in a single-master cluster. This lesson steps through the architecture and explains how the conflict resolution works.

![alt text](image-52.png)

![alt text](image-53.png)

![alt text](image-54.png)

![alt text](image-55.png)