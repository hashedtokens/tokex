# Tokex

_Low latency, high frequency, unordered, decentralized multi-party token exchange library with real-time acknowledgement_

## Core Idea
`Tokens` are vital to any service layer communication regardless of the encoding properties. In a vast majority of scenarios where tokens act like a reference for applications to fetch information, the acknowledgement factor is often absent. Lack of implicit acknowledgement leads to network congestion with _retry polling_. REST API protocol ensures acknowledgement is implicit, but doesn't allow multi-casting, and this library bridges the gap. 

Equivalent to **`Multicast over TCP`**

### Applications
* PubSub with acknowledgement
* Token mediated transaction orchestration

  
