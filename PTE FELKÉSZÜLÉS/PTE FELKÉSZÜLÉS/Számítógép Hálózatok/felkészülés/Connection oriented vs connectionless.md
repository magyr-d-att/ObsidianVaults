
![[Pasted image 20260910144743.png]]
- C-oriented -> Modeled after telephone.

Connection established -> negotiation -> (Accept/Reject/Counteroffer)

**Negotiation** is about the parameters used, quality of service, message size etc.

**Circuit** -> Connection with associated resources.

Two variations: Message sequences, Byte streams. Byte streams have no message borders.

- Connectionless -> Modeled after postal system

Each message carries the destination. 

Store and forward stitching: Intermediate node receives hte message in full, then sends.

Cut-through-stitching: The message is sent before fully receiving.

Most popular version is **Datagram service**, no guarantee or acknowledgement that it arrives, but high probability.  Sometimes you want the convenience of not having to make a connection, but you want reliability, there is also the acknowledged Datagram. (Text messaging e.g)

**Request-reply** service: 
Sender transmits a datagram with request -> Reply contains answer. Frequently used in client-server model. 
