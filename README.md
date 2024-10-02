# OSI-Model
The OSI (Open Systems Interconnection) model is a conceptual framework used to understand and implement network communications in seven layers. Here’s a brief overview of each layer:

1. **Physical Layer**:
   - **Function**: Transmits raw bit streams over a physical medium.
   - **Components**: Cables, switches, network interface cards (NICs).
   - **Key Points**: Deals with electrical, optical, and radio signals.

2. **Data Link Layer**:
   - **Function**: Provides node-to-node data transfer and error detection/correction.
   - **Components**: MAC addresses, switches, bridges.
   - **Key Points**: Ensures reliable transmission between directly connected nodes.

3. **Network Layer**:
   - **Function**: Manages routing of data packets between devices across different networks.
   - **Components**: Routers, IP addressing.
   - **Key Points**: Handles logical addressing and determines the best path for data.

4. **Transport Layer**:
   - **Function**: Provides reliable or unreliable delivery, error recovery, and flow control.
   - **Components**: TCP, UDP.
   - **Key Points**: Ensures complete data transfer and manages session establishment.

5. **Session Layer**:
   - **Function**: Manages sessions between applications, controlling the dialog.
   - **Components**: APIs for managing sessions.
   - **Key Points**: Establishes, maintains, and terminates connections.

6. **Presentation Layer**:
   - **Function**: Translates data between the application and the network.
   - **Components**: Data format translation, encryption, compression.
   - **Key Points**: Ensures data is in a usable format for the application layer.

7. **Application Layer**:
   - **Function**: Interfaces directly with end-user applications.
   - **Components**: HTTP, FTP, SMTP, DNS.
   - **Key Points**: Provides network services to applications and end-users.

This layered approach helps standardize network communications, making it easier to troubleshoot and develop new networking technologies.
