# 2pc-protocol

A two-phase commit is a standardized protocol that ensures that a database commit is implementing in the situation where a commit operation must be broken into two separate parts.

In database management, saving data changes is known as a commit and undoing changes is known as a rollback. Both can be achieved easily using transaction logging when a single server is involved, but when the data is spread across geographically-diverse servers in distributed computing (i.e., each server being an independent entity with separate log records), the process can become more tricky.

How to run:
1. Run the server code as
  javac Server.java
  java Server
2. Run the clients(multiple)
    javac Client.java
    java Client
3. Enter the name and followed by COMMIT
4. When server gets commit from all clients, it gets back to clients with GLOBAL_COMMIT.





References:
https://en.wikipedia.org/wiki/Two-phase_commit_protocol
