# Load Balancer

A versatile Load Balancer implemented in **C++**, supporting multiple load balancing algorithms such as Least Connection, Round Robin, and Routed. The project also integrates hashing and custom queuing mechanisms to efficiently balance requests across multiple service destinations.

---

## Features

- **Multiple Load Balancing Algorithms**:
  - **Least Connection**: Routes requests to the server with the least active connections.
  - **Round Robin**: Distributes requests in a cyclic order among servers.
  - **Routed**: Directs requests based on a specific routing key.
- **Hashing Mechanism**: Ensures requests with the same key are consistently routed to the same server.
- **Custom Queuing**: Manages incoming requests and balances them across servers.

---
