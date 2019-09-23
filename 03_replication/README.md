# Distributed Systems Notes

## Replication

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
  * **Writes When a Node is Down**
    * **Read Repair and Anti-Entropy
  * **Quorum Consistency**
    * **Quorum Consistency Limitations**
    * **Monitoring Staleness**
    * **Sloppy Quorums and Hinted Handoff**
  * **Multi-Datacenter Operation
* **Concurrent Write Handling**

**Bold indicates it's incomplete, but is planned/in progress**