# CMPE273-Group12

# Distributed Systems Project Ideas

## 1. Kubernetes Self-Healing Service Controller

- **Objective:** Develop a custom Kubernetes controller that manages fault-tolerant distributed workloads.
- **Description:** The controller will monitor worker health, maintain the desired number of replicas, restart failed workers, and retry unfinished tasks.
- **Distributed Systems Concepts:** Failure detection, replication, reconciliation, fault tolerance, load balancing, and eventual consistency.
- **Evaluation:** Measure recovery time, task completion rate, system availability, and behavior during worker or network failures.
- **Expected Outcome:** A Kubernetes-based prototype demonstrating automated recovery and management of distributed services.

## 2. Fault-Tolerant Distributed Task Queue

- **Objective:** Build a distributed task queue that reliably assigns jobs to multiple workers.
- **Description:** Users will submit tasks through an API, and workers will process them concurrently. The system will support acknowledgments, retries, timeouts, and recovery when workers fail.
- **Distributed Systems Concepts:** Message delivery guarantees, idempotency, replication, concurrency, failure recovery, and load balancing.
- **Evaluation:** Compare throughput, latency, task duplication, and recovery behavior under different failure scenarios.
- **Expected Outcome:** A reliable task-processing system that continues operating despite worker crashes or temporary communication failures.

## 3. Distributed Key-Value Store Using Raft

- **Objective:** Implement a replicated key-value store using the Raft consensus algorithm.
- **Description:** The system will support basic read and write operations across multiple nodes, with automatic leader election and log replication.
- **Distributed Systems Concepts:** Consensus, leader election, replicated state machines, strong consistency, network partitions, and fault tolerance.
- **Evaluation:** Test data consistency, leader failover time, availability, and behavior when nodes crash or messages are delayed.
- **Expected Outcome:** A working distributed database prototype that maintains consistent state despite node failures.