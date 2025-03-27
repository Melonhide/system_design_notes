# ✅ Chapter 1: Scale from Zero to Millions of Users

NoSQL Database Category:
1. key-value stores
2. graph stores
3. column stores
4. document stores

NoSQL Database best for:
1. Application requires super-low latency
2. Data are unstructured/no relational data
3. Only need to serialize and deserialize data
4. Store a massive amount of data

Vertical Scaling(Scale Up)(Traffic Low): Add more power to servers
Horizontal Scaling(Scale-out)(Large Scale Applicaion): Add more servers

Vertical Scaling(Scale Up) Limitation:
1. Has hard limit
2. Does not have failover and redundancy

Load Balancer communicates with web servers through private IP address. Private IP Address is reachable only between servers in the same network. Private IP Address is unreachable over the internet.

Master Database only supports write operations
Slave Database only supports read operations

Slave Database goes offline, redirect read operations to master database temporarily or to other slave database
Master Database goes offline, a slave database will be promoted to a new master (data recovery scripts may need)

Consideration for Using Cache
1.
2.
3.
4.
5.

Consideration for using a CDN
1.
2.
3.
4.

Stateful Architecture



Technical Challenges for multi-data center setup
1.
2.
3.
4.
5.

Metrics:
1.
2.
3.

Database Scaling:
    Vertical Scaling:
        1.
        2.
        3.

    Horizontal Scaling:

        Challenges:
        1.
        2.
        3.


Key Conclusions:
1.
2.
3.
4.
5.
6.
7.
8.



