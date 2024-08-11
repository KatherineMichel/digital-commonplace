# Distributed Systems

### Patterns of Distributed Systems

<!--
## Distributed Systems Engineering

Book
https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/

https://github.com/pingcap/talent-plan | pingcap/talent-plan: open source training courses about distributed database and distributed systems

https://ferd.ca/a-distributed-systems-reading-list.html
https://news.ycombinator.com/from?site=ferd.ca
https://news.ycombinator.com/item?id=39303160
https://dancres.github.io/Pages/ | Distributed Systems Reading List

List of Algorithms
http://www.cs.yale.edu/homes/aspnes/classes/465/notes.pdf | Notes on Theory of Distributed Systems

https://newpublic.org/article/1668/a-visual-guide-to-decentralization | A visual guide to decentralization | New_ Public Magazine

https://www.geeksforgeeks.org/types-of-distributed-system/

Distributed Systems
https://en.wikipedia.org/wiki/Distributed_computing
https://www.atlassian.com/microservices/microservices-architecture/distributed-architecture
https://www.atlassian.com/microservices/microservices-architecture/distributed-architecture#:~:text=A%20distributed%20system%20is%20a,of%20failure%20from%20a%20system. | What is a distributed system? | Atlassian
https://www.splunk.com/en_us/blog/learn/distributed-systems.html

https://www.allthingsdistributed.com

5.6 Leader Election using BFS
https://jukkasuomela.fi/da2020/da2020.pdf | Distributed Algorithms 2020
-->

<!--
https://en.wikipedia.org/wiki/Multiversion_concurrency_control | Multiversion concurrency control - Wikipedia
https://en.wikipedia.org/wiki/Non-lock_concurrency_control

https://en.wikipedia.org/wiki/Three-phase_commit_protocol | Three-phase commit protocol - Wikipedia
https://en.wikipedia.org/wiki/Two-phase_commit_protocol | Two-phase commit protocol - Wikipedia
https://en.wikipedia.org/wiki/Two-phase_locking | Two-phase locking - Wikipedia
https://en.wikipedia.org/wiki/Atomic_commit | Atomic commit - Wikipedia
https://en.wikipedia.org/wiki/Non-blocking_algorithm | Non-blocking algorithm - Wikipedia

https://en.wikipedia.org/wiki/Distributed_algorithm | Distributed algorithm - Wikipedia
https://en.wikipedia.org/wiki/Replication_(computing) | Replication (computing) - Wikipedia

https://en.wikipedia.org/wiki/Paxos_(computer_science) | Paxos (computer science) - Wikipedia
https://en.wikipedia.org/wiki/Raft_(algorithm) | Raft (algorithm) - Wikipedia
https://en.wikipedia.org/wiki/Consensus_(computer_science) | Consensus (computer science) - Wikipedia
https://en.wikipedia.org/wiki/Leader_election | Leader election - Wikipedia

Serial Algorithm- RAM
https://en.wikipedia.org/wiki/Parallel_algorithm | Parallel algorithm - Wikipedia

## Raft

https://thesecretlivesofdata.com/raft/ | Raft
https://raft.github.io/ | Raft Consensus Algorithm
-->

<!--
https://martinfowler.com/articles/patterns-of-distributed-systems/ | Patterns of Distributed Systems
https://www.compileralchemy.com/blog/praise-for-patterns-of-distributed-computing/ | Praise for Patterns of Distributed Computing
https://www.amazon.com/Patterns-Distributed-Systems-Addison-Wesley-Signature/dp/0138221987/ref=asc_df_0138221987/?tag=hyprod-20&linkCode=df0&hvadid=693617400601&hvpos=&hvnetw=g&hvrand=1540816189329461302&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9024386&hvtargid=pla-2087849617622&psc=1&mcid=070f6a23df7b35429086d7aacabf3e13&gad_source=1 | Patterns of Distributed Systems (Addison-Wesley Signature Series (Fowler)): Joshi, Unmesh: 9780138221980: Amazon.com: Books

Gossip Dissemination
Use a random selection of nodes to pass on information to ensure it reaches all the nodes in the cluster without flooding the network
https://martinfowler.com/articles/patterns-of-distributed-systems/gossip-dissemination.html

HeartBeat
Show a server is available by periodically sending a message to all the other servers.
https://martinfowler.com/articles/patterns-of-distributed-systems/heartbeat.html

Lease
Use time-bound leases for cluster nodes to coordinate their activities.
https://martinfowler.com/articles/patterns-of-distributed-systems/lease.html


## Clock

Clock-Bound Wait
Wait to cover the uncertainty in time across cluster nodes before reading and writing values so that values can be correctly ordered across cluster nodes.
https://martinfowler.com/articles/patterns-of-distributed-systems/clock-bound-wait.html

Generation Clock
A monotonically increasing number indicating the generation of the server.
https://martinfowler.com/articles/patterns-of-distributed-systems/generation-clock.html

Hybrid Clock
Use a combination of system timestamp and logical timestamp to have versions as date and time, which can be ordered
https://martinfowler.com/articles/patterns-of-distributed-systems/hybrid-clock.html

Lamport Clock
Use logical timestamps as a version for a value to allow ordering of values across servers
https://martinfowler.com/articles/patterns-of-distributed-systems/lamport-clock.html

## Consistency, Election, Quorum, Consensus Algorithm

Consistent Core
Maintain a smaller cluster providing stronger consistency to allow the large data cluster to coordinate server activities without implementing quorum-based algorithms.
https://martinfowler.com/articles/patterns-of-distributed-systems/consistent-core.html

Emergent Leader
Order cluster nodes based on their age within the cluster to allow nodes to select a leader without running an explicit election.
https://martinfowler.com/articles/patterns-of-distributed-systems/emergent-leader.html

Leader and Followers
Have a single server to coordinate replication across a set of servers.
https://martinfowler.com/articles/patterns-of-distributed-systems/leader-follower.html

Majority Quorum
Avoid two groups of servers making independent decisions by requiring majority for taking every decision.
https://martinfowler.com/articles/patterns-of-distributed-systems/majority-quorum.html

Paxos
Use two consensus building phases to reach safe consensus even when nodes disconnect
https://martinfowler.com/articles/patterns-of-distributed-systems/paxos.html

## Read Requests

Follower Reads
Serve read requests from followers to achieve better throughput and lower latency
https://martinfowler.com/articles/patterns-of-distributed-systems/follower-reads.html

## Requests

Idempotent Receiver
Identify requests from clients uniquely so you can ignore duplicate requests when client retries
https://martinfowler.com/articles/patterns-of-distributed-systems/idempotent-receiver.html

Request Batch
Combine multiple requests to optimally utilise the network
https://martinfowler.com/articles/patterns-of-distributed-systems/request-batch.html

Request Pipeline
Improve latency by sending multiple requests on the connection without waiting for the response of the previous requests.
https://martinfowler.com/articles/patterns-of-distributed-systems/request-pipeline.html

Request Waiting List
Track client requests which require responses after the criteria to respond is met based on responses from other cluster nodes.
https://martinfowler.com/articles/patterns-of-distributed-systems/request-waiting-list.html

Single-Socket Channel
Maintain the order of the requests sent to a server by using a single TCP connection
https://martinfowler.com/articles/patterns-of-distributed-systems/single-socket-channel.html

Singular Update Queue
Use a single thread to process requests asynchronously to maintain order without blocking the caller.
https://martinfowler.com/articles/patterns-of-distributed-systems/singular-update-queue.html

## Updates

State Watch 
Notify clients when specific values change on the server
https://martinfowler.com/articles/patterns-of-distributed-systems/state-watch.html

Two-Phase Commit
Update resources on multiple nodes in one atomic operation
https://martinfowler.com/articles/patterns-of-distributed-systems/two-phase-commit.html | Two-Phase Commit

Version Vector 
Maintain a list of counters, one per cluster node, to detect concurrent updates

Versioned Value
Store every update to a value with a new version, to allow reading historical values.

## Partitions

Fixed Partitions
Keep the number of partitions fixed to keep the mapping of data to partition unchanged when the size of a cluster changes.
https://martinfowler.com/articles/patterns-of-distributed-systems/fixed-partitions.html

Key-Range Partitions
Partition data in sorted key ranges to efficiently handle range queries.
https://martinfowler.com/articles/patterns-of-distributed-systems/key-range-partitions.html

## Logs

Segmented Log
Split log into multiple smaller files instead of a single large file for easier operations.
https://martinfowler.com/articles/patterns-of-distributed-systems/segmented-log.html

Write-Ahead Log
Provide durability guarantee without the storage data structures to be flushed to disk, by persisting every state change as a command to the append only log.

Replicated Log
Keep the state of multiple nodes synchronized by using a write-ahead log that is replicated to all the cluster nodes.
https://martinfowler.com/articles/patterns-of-distributed-systems/replicated-log.html

High-Water Mark
An index in the write-ahead log showing the last successful replication.
https://martinfowler.com/articles/patterns-of-distributed-systems/high-watermark.html

Low-Water Mark
An index in the write-ahead log showing which portion of the log can be discarded.
https://martinfowler.com/articles/patterns-of-distributed-systems/low-watermark.html
-->

## Gregor Hohpe

<!--
https://architectelevator.com/blog/ | Architect Elevator Blog - The Architect Elevator
https://architectelevator.com/architecture/architect-bookshelf/ | The Architect’s Path (Part 2 - Bookshelf) - The Architect Elevator
https://architectelevator.com/architecture/classic-architecture-books/ | Old Books that Every Architect Should Read - The Architect Elevator
Platform Strategy
https://leanpub.com/platformstrategy
-->

### Enterprise Integration Patterns

<!--
https://www.enterpriseintegrationpatterns.com/patterns/messaging/
https://www.enterpriseintegrationpatterns.com/ramblings/eip1_examples_updated.html
https://enterpriseintegrationpatterns.com/patterns/messaging/toc.html
-->

<!--
Modern examples
https://www.enterpriseintegrationpatterns.com/ramblings/eip1_examples_updated.html
Code
https://github.com/spac3lord/eip

Publish-Subscribe Channel	Google Cloud Pub/sub
Dead Letter Channel	Amazon SQS, Kafka Connect
Return Address	GoLang
Message Expiration	Azure Service Bus, Amazon EventBridge, Google Cloud PubSub
Content-based Router	Apache Camel
Scatter-Gather	Serverless Loan Broker on AWS, Mulesoft ESB, Azure Durable Functions: Fan out/fan in
Message Filter	RabbitMQ
Aggregator	Serverless Loan Broker on AWS (Lambda, DynamoDB), Serverless Loan Broker on GCP (Cloud Function, Datastore)
Process Manager	Serverless Loan Broker with AWS Step Functions, Serverless Loan Broker with GCP Workflows
Content Enricher	Amazon EventBridge Pipes
Transactional Client	Amazon SQS
Event-driven Consumer	RabbitMQ
Competing Consumers	Apache Kafka
Channel Purger	Amazon SQS


Integration Styles
Introduction to Integration Styles
https://www.enterpriseintegrationpatterns.com/patterns/messaging/Chapter1.html
File Transfer	How can I integrate multiple applications so that they work together and can exchange information?
Shared Database	How can I integrate multiple applications so that they work together and can exchange information?
Remote Procedure Invocation	How can I integrate multiple applications so that they work together and can exchange information?
How can I integrate multiple applications so that they work together and can exchange information?

Messaging Systems
Introduction to Messaging Systems	 
Message Channel	How does one application communicate with another using messaging?
Message	How can two applications connected by a message channel exchange a piece of information?
Pipes and Filters	How can we perform complex processing on a message while maintaining independence and flexibility?
Message Router	How can you decouple individual processing steps so that messages can be passed to different filters depending on a set of conditions?
Message Translator	How can systems using different data formats communicate with each other using messaging?
Message Endpoint	How does an application connect to a messaging channel to send and receive messages?

Messaging Channels
Introduction to Messaging Channels	 
Point-to-Point Channel	How can the caller be sure that exactly one receiver will receive the document or perform the call?
Publish-Subscribe Channel	How can the sender broadcast an event to all interested receivers?
Datatype Channel	How can the application send a data item such that the receiver will know how to process it?
Invalid Message Channel	How can a messaging receiver gracefully handle receiving a message that makes no sense?
Dead Letter Channel	What will the messaging system do with a message it cannot deliver?
Guaranteed Delivery	How can the sender make sure that a message will be delivered, even if the messaging system fails?
Channel Adapter	How can you connect an application to the messaging system so that it can send and receive messages?
Messaging Bridge	How can multiple messaging systems be connected so that messages available on one are also available on the others?
Message Bus	What is an architecture that enables separate applications to work together, but in a decoupled fashion such that applications can be easily added or removed without affecting the others?

Message Construction
Introduction to Message Construction	 
Command Message	How can messaging be used to invoke a procedure in another application?
Document Message	How can messaging be used to transfer data between applications?
Event Message	How can messaging be used to transmit events from one application to another?
Request-Reply	When an application sends a message, how can it get a response from the receiver?
Return Address	How does a replier know where to send the reply?
Correlation Identifier	How does a requestor that has received a reply know which request this is the reply for?
Message Sequence	How can messaging transmit an arbitrarily large amount of data?
Message Expiration	How can a sender indicate when a message should be considered stale and thus shouldn’t be processed?
Format Indicator	How can a message’s data format be designed to allow for possible future changes?

Interlude: Simple Messaging

Message Routing
Introduction to Message Routing	 
Content-Based Router	How do we handle a situation where the implementation of a single logical function (e.g., inventory check) is spread across multiple physical systems?
Message Filter	How can a component avoid receiving uninteresting messages?
Dynamic Router	How can you avoid the dependency of the router on all possible destinations while maintaining its efficiency?
Recipient List	How do we route a message to a list of dynamically specified recipients?
Splitter	How can we process a message if it contains multiple elements, each of which may have to be processed in a different way?
Aggregator	How do we combine the results of individual, but related messages so that they can be processed as a whole?
Resequencer	How can we get a stream of related but out-of-sequence messages back into the correct order?
Composed Message Processor	How can you maintain the overall message flow when processing a message consisting of multiple elements, each of which may require different processing?
Scatter-Gather	How do you maintain the overall message flow when a message needs to be sent to multiple recipients, each of which may send a reply?
Routing Slip	How do we route a message consecutively through a series of processing steps when the sequence of steps is not known at design-time and may vary for each message?
Process Manager	How do we route a message through multiple processing steps when the required steps may not be known at design-time and may not be sequential?
Message Broker	How can you decouple the destination of a message from the sender and maintain central control over the flow of messages?

Message Transformation
Introduction to Message Transformation	 
Envelope Wrapper	How can existing systems participate in a messaging exchange that places specific requirements on the message format, such as message header fields or encryption?
Content Enricher	How do we communicate with another system if the message originator does not have all the required data items available?
Content Filter	How do you simplify dealing with a large message, when you are interested only in a few data items?
Claim Check	How can we reduce the data volume of message sent across the system without sacrificing information content?
Normalizer	How do you process messages that are semantically equivalent, but arrive in a different format?
Canonical Data Model	How can you minimize dependencies when integrating applications that use different data formats?

Interlude: Composed Messaging

Messaging Endpoints
Introduction to Messaging Endpoints	 
Messaging Gateway	How do you encapsulate access to the messaging system from the rest of the application?
Messaging Mapper	How do you move data between domain objects and the messaging infrastructure while keeping the two independent of each other?
Transactional Client	How can a client control its transactions with the messaging system?
Polling Consumer	How can an application consume a message when the application is ready?
Event-Driven Consumer	How can an application automatically consume messages as they become available?
Competing Consumers	How can a messaging client process multiple messages concurrently?
Message Dispatcher	How can multiple consumers on a single channel coordinate their message processing?
Selective Consumer	How can a message consumer select which messages it wishes to receive?
Durable Subscriber	How can a subscriber avoid missing messages while it’s not listening for them?
Idempotent Receiver	How can a message receiver deal with duplicate messages?
Service Activator	How can an application design a service to be invoked both via various messaging technologies and via non-messaging techniques?

System Management
Introduction to System Management	 
Control Bus	How can we effectively administer a messaging system that is distributed across multiple platforms and a wide geographic area?
Detour	How can you route a message through intermediate steps to perform validation, testing or debugging functions?
Wire Tap	How do you inspect messages that travel on a point-to-point channel?
Message History	How can we effectively analyze and debug the flow of messages in a loosely coupled system?
Message Store	How can we report against message information without disturbing the loosely coupled and transient nature of a messaging system?
Smart Proxy	How can you track messages on a service that publishes reply messages to the Return Address specified by the requestor?
Test Message	What happens, though, if a component is actively processing messages, but garbles outgoing messages due to an internal fault?
Channel Purger	How can you keep 'left-over' messages on a channel from disturbing tests or running systems?
-->
