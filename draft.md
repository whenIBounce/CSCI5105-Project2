 replication takes a redundant node one step further; it ensures that the redundant node (a replica) is identical to all of its other copies

 If we created just a simple redundant node, there is nothing in place within our system that will ensure that the redundant node will 1) know that something changed and 2) will update itself or be updated by someone else to have the correct state

 Replication makes a distributed system more:
 1. Reliable: it is more likely to be available + fault tolerant
 2. Peformant: it is more likely to respond quickly and handle a high throughput
 3. Easy to scale: it is much easier to handle a higher workload and serve more locations

the concept of replication needs one other thing to really work well: **consistency**.

