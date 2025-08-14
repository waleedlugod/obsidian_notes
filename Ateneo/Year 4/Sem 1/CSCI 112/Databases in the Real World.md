# The Well Architected Framework
* developed by AWS
* uses general concepts
* 6 pillars: Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, and Sustainability

# Operational Excellence
* ability to support required workloads effectively
* performance and availability for databases
## Database performance
* required latency: time a request travels to a server and back
* Input Output per Second (IOPS): the performance of storage devices to process requests
* Read/Write throughput: amount of data that can be read or written in a database for a specific amount of time
* Concurrency: capability to process requests at the same time

IOPS vs throughput
IOPS: transactions per second
throughput: amount of data transferred per second

## Availability Considerations
* Read replicas: servers dedicated to read operations
* Clustering: decoupled servers use to distribute database load
* Geo-distributed deployments: servers located in separate physical locations

## SQL vs Document DB
SQL
* Online transaction processing (OLTP)
* Online analytical processing (OLAP)

Document DB
* high performance computing
* IoT
* Logging
* Session State
* Messaging

## Security
* Principle of least privilege: access to only who needs it

## Reliability
* address failures automatically
* Self-healing: switch traffic to an available server while spawning a new server to replace a faulty one
* Auto-scaling: scale and meet demand

Serverless architecture
* server is abstracted from developers
* high availability
* no server maintenance
* automatic replications and backups

## Performance Efficiency
* design and architecture reviews
* decommissioning of unused resources
* resource utilization tracking
* right service of the right use case

Correct database for correct workload
* File system
* Object store
* Relational databases
* Non-relational databases

The Vs of Big Data
* Volume: how big the data is
* Velocity: How fast the data is moving
* Variety: In what formats the data come in

## Cost Optimization
* implement financial management
* automated budget tracking
* resource optimization for under utilized resources