# Unit 4: Mobile Distributed Computing Systems and Architecture — Fill in the Blanks

**Course:** Mobile Computing / Distributed Systems  
**Format:** Fill in each blank with the correct term, phrase, or concept.

---

## Session 1: Distributed Systems Architecture

1. Distributed systems ________ refers to the organization and interaction of components in a distributed system.
2. In a ________ architecture, all nodes have equal roles and can provide and consume resources.
3. In a ________ architecture, clients request services from centralized servers.
4. A ________ architecture divides system functionality into layers, each providing services to the layer above.
5. ________ architecture organizes components as independent services that communicate over a network.
6. A ________ broker acts as an intermediary that coordinates communication between clients and servers.
7. The ________ tier in a three-tier architecture typically handles user interaction.
8. The ________ tier processes business logic in a three-tier architecture.
9. The ________ tier stores and manages data in a three-tier architecture.
10. ________ is a design principle where components are separated into independent modules.
11. A ________ architecture uses multiple servers to process requests and improve scalability.
12. ________ computing allows resources to be distributed and accessed across multiple systems.
13. An ________-driven architecture reacts to events such as messages or state changes.
14. ________ refers to how well an architecture can handle growth in users, data, or workload.
15. Architectural ________ involves trade-offs among performance, scalability, reliability, and security.

---

## Session 2: Distributed Systems Communication

1. ________ is the exchange of data between processes or nodes in a distributed system.
2. ________ communication requires sender and receiver to be active at the same time.
3. ________ communication allows sender and receiver to operate at different times.
4. ________ passing is a method where processes communicate by sending and receiving messages.
5. ________ Procedure Call (RPC) allows a program to execute a procedure on a remote system as if it were local.
6. ________ Object Invocation (RMI) allows an object in one system to invoke methods on an object in another system.
7. ________ is a middleware technology that enables communication between distributed objects.
8. A ________ is a data format used to package information for transmission.
9. ________ is the process of converting data structures into a format suitable for transmission or storage.
10. ________ is the reverse process of reconstructing data from a transmitted format.
11. ________ sockets provide connection-oriented communication, often using TCP.
12. ________ sockets provide connectionless communication, often using UDP.
13. ________ is the delay involved in transmitting messages across a network.
14. Communication ________ define rules for formatting, transmitting, and receiving messages.
15. Reliable communication requires handling errors, packet loss, and ________.

---

## Session 3: Mobile Information Systems

1. A ________ information system provides access to information and services through mobile devices.
2. Mobile information systems support users who are ________ and need access to data anywhere.
3. A key component of mobile information systems is ________ connectivity.
4. Mobile information systems often rely on ________ databases to store and retrieve data.
5. ________ refers to adapting information presentation based on user location, device, or preferences.
6. ________-aware services use user location to provide relevant information.
7. Mobile information systems must address limited screen size and ________ life.
8. ________ synchronization ensures mobile data remains consistent with central systems.
9. ________ access control protects sensitive information in mobile systems.
10. Mobile information systems can support business processes such as sales, inventory, and ________ service.
11. ________ computing allows mobile information systems to offload processing to remote servers.
12. A major challenge is maintaining data ________ when devices disconnect or reconnect.
13. ________ interfaces should be simple and responsive for mobile users.
14. Mobile information systems often use ________ notifications to deliver timely updates.
15. ________ is essential to protect data transmitted over wireless networks.

---

## Session 4: Distributed Files

1. A ________ file system allows files to be stored and accessed across multiple networked machines.
2. In a distributed file system, users should be able to access files as if they were ________.
3. ________ transparency hides the physical location of files from users.
4. ________ transparency allows files to be moved without changing how users access them.
5. ________ transparency allows multiple file replicas to appear as one file.
6. File ________ is the process of storing copies of files on multiple servers.
7. ________ consistency ensures that updates to a file are seen correctly by users.
8. A ________ server stores and manages files in a distributed file system.
9. ________ allows users to store files locally for faster access when disconnected.
10. File ________ controls determine who can read, write, or execute files.
11. ________ is the process of resolving conflicts when multiple copies of a file are modified.
12. Distributed file systems must handle network ________ and node failures.
13. ________ is a common operation that retrieves a file or data block from a server.
14. ________ improves performance by storing recently accessed data closer to the user.
15. Scalability in distributed file systems allows more storage and users to be added without major ________.

---

## Session 5: Distributed Mobile Database Systems

1. A distributed ________ database system stores data across multiple sites while supporting mobile users.
2. Mobile databases must handle frequent ________ and reconnection of devices.
3. ________ replication copies database data to multiple locations for availability.
4. ________ fragmentation divides database tables into smaller parts stored at different sites.
5. ________ fragmentation divides a table by rows.
6. ________ fragmentation divides a table by columns.
7. ________ synchronization keeps mobile and server databases consistent.
8. A mobile database may operate in ________ mode when network connectivity is unavailable.
9. ________ processing ensures database transactions follow ACID properties.
10. ________ control prevents conflicts when multiple users update data simultaneously.
11. ________ commit protocols coordinate transaction completion across distributed sites.
12. Data ________ ensures users receive correct and consistent query results.
13. Mobile database systems must consider bandwidth, latency, and ________ consumption.
14. ________ queries retrieve data from multiple distributed database sites.
15. A ________ server coordinates database operations and transaction management.

---

## Session 6: Replication in Mobile Distributed Systems

1. ________ is the process of maintaining multiple copies of data or services at different locations.
2. Replication improves data ________ by allowing access even if one copy is unavailable.
3. Replication can improve ________ by allowing users to access a nearby copy.
4. A challenge of replication is maintaining ________ among copies.
5. ________ replication updates all replicas as part of the same transaction.
6. ________ replication updates replicas after the primary update, possibly with delay.
7. In ________-primary replication, one node handles updates and propagates them to others.
8. In ________-primary replication, multiple nodes can accept updates.
9. ________ conflicts occur when different replicas are updated independently.
10. Conflict ________ is the process of detecting and resolving conflicting updates.
11. Replication increases ________ overhead because updates must be propagated.
12. ________ consistency allows temporary differences between replicas.
13. Strong ________ ensures all users see the same data immediately after updates.
14. Mobile environments make replication challenging due to intermittent ________.
15. Replication strategies must balance consistency, availability, and ________.
