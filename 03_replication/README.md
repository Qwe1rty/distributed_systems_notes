# Distributed Systems Notes

## Replication

This chapter is about data replication strategies, nuances, and consistency issues that occur
when trying to replicate the same data onto different computers

* Single-Leader Replication
  * Synchronous vs. Asynchronous Replication
    * Synchronous Replication: Chain Replication
  * Recovery
    * Recovery: Followers (Catch-up)
    * Recovery: Leaders (Failover)
  * Replication Logs
    * Statement-Based Logs
    * Write-Ahead Logs
    * Logical Logs (Row-Based Logs)
    * Trigger-Based Replication
  * Replication Lag/Latency
    * Read-Your-Writes
    * Monotonic Reads
    * Transactions as a Solution
* Multi-Leader Replication
  * Multi-Leader Use Cases
    * Multi-Datacenter Operation
    * Offline Clients
    * Collaborative Editing
  * Conflict Resolution
    * Conflict Avoidance
    * Conflict Resolution: Consistent State Convergence
    * Conflict Resolution: Resolution Logic
  * Multi-Leader Replication Topologies
* **Leaderless Replication**
  * Recovery
    * Read Repair
    * Anti-Entropy
  * Quorum Consistency
    * Read-Your-Writes and Writes-Follow-Reads
    * Monotonic Writes
    * Quorum Consistency Limitations
    * Monitoring Staleness
    * The CAP Theorem and Sloppy Quorums
  * Multi-Datacenter Operation
  * Concurrent Write Handling
    * **"Happens-Before" and Causality**
    * **Value Merging**
    * **Last Write Wins**
    * **Version Vectors**

**Bold indicates it's incomplete, but is planned/in progress**