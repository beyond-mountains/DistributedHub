# vision/guideline

- [Cloud Databases: New Techniques, Challenges, and Opportunities-VLDB22](https://www.vldb.org/pvldb/vol15/p3758-li.pdf)
- [The Case for Distributed Shared-Memory Databases with RDMA-Enabled Memory Disaggregation-VLDB22](https://arxiv.org/pdf/2207.03027.pdf)
- [Disaggregated Database Systems-SIGMOD23](https://www.cs.purdue.edu/homes/csjgwang/pubs/SIGMOD23_Tutorial_DisaggregatedDB.pdf)

# Memory Disaggregation with RDMA in RDBMS

## Lock Management

- [Distributed Lock Management with RDMA: Decentralization without Starvation-SIGMOD18](https://www.mosharaf.com/wp-content/uploads/dslr-sigmod18.pdf):star:

## Memory Management

- [Efficient Distributed Memory Management with RDMA and Caching-VLDB18](https://vldb.org/pvldb/vol11/p1604-cai.pdf)
- [Patronus: High-Performance and  Protective Remote Memory-FAST23](https://www.usenix.org/system/files/fast23-yan.pdf)

- [D-RDMA: Bringing Zero-Copy RDMA to Database Systems-CIDR22](https://www.cidrdb.org/cidr2022/papers/p77-ryser.pdf)
- [When Cloud Storage Meets RDMA-NSDI21](https://www.usenix.org/system/files/nsdi21-gao.pdf)

## Replication

- [Rethinking database high availability with RDMA networks-VLDB19](https://vldb.org/pvldb/vol12/p1637-zamanian.pdf)

## Partition

- [Chiller: Contention-centric Transaction Execution and Data Partitioning for Fast Networks-SIGMOD20](https://arxiv.org/pdf/1811.12204v1.pdf):star:

## DBMS

- [PilotDB-ASPLOS23](https://ashraf.aboulnaga.me/pubs/asplos23pilotdb.pdf)
- [PolarDB Serverless-SIGMOD21](https://dl.acm.org/doi/pdf/10.1145/3448016.3457560):star:
- [Towards Cost-Effective and Elastic Cloud Database Deployment via Memory Disaggregation-VLDB21](https://vldbarc.org/pvldb/vol14/p1900-zhang.pdf)

# CC Protocol

- TCP/IP

  - [DBx1000-VLDB14](https://www.vldb.org/pvldb/vol8/p209-yu.pdf)

  - [Deneva-VLDB17](https://pages.cs.wisc.edu/~yxy/cs839-s20/papers/p553-harding.pdf)

- RDMA

  - [RCC-IEEE Transactions on Cloud Computing 23](https://alchem.usc.edu/portal/static/download/rdma_tx.pdf)

  - [RedT-VLDB23](https://www.vldb.org/pvldb/vol16/p1372-lu.pdf):star:

# consistency

- [MDCC-Eurosys13](http://mdcc.cs.berkeley.edu/mdcc.pdf)

- [TAPIR-SOSP15](https://dl.acm.org/doi/pdf/10.1145/2815400.2815404)

- [PolarDB-SCC-VLDB23](https://www.vldb.org/pvldb/vol16/p3754-chen.pdf):star:

- 2PC、determinism

  - [The Case for Determinism in Database Systems-vldb10](http://dslam.cs.umd.edu/determinism-vldb10.pdf):star:

    > 摘自mit6.830课后问题：
    >
    > 1. What is the advantage of deterministic ordering of transactions? What is the cost of it?
    > 2. How does the paper deal with transactions that do not issue all of their statements in advance, or where the locks a transaction acquires depend on previous statements in the transaction?

  - [Aria-VLDB20](https://dspace.mit.edu/bitstream/handle/1721.1/133983/3407790.3407808.pdf;jsessionid=A1DA166B700E34766D01493109B8063D?sequence=2)

  - [COCO-VLDB21](https://pages.cs.wisc.edu/~yxy/pubs/coco.pdf)

  - [Cornus-VLDB22](https://www.vldb.org/pvldb/vol16/p379-guo.pdf)

  - [Primo -ICDE23](https://arxiv.org/pdf/2302.12517.pdf):star:

- replication、re-partition、scale

  - [STAR: Scaling Transactions through Asymmetric Replication-VLDB18](https://arxiv.org/pdf/1811.02059.pdf)
  - [Asymmetric-Partition Replication for Highly Scalable Distributed Transaction Processing in Practice-VLDB20](https://www.vldb.org/pvldb/vol13/p3112-lee.pdf) 





