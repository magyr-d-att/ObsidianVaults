[[Subnets]]

![[Pasted image 20260911123300.png]]

Core idea: Data should not be lost even if some machines were to be turned off.

Link Layer:
Describes what the links must do to meet the needs of the connectionless internet layer.

Internet Layer:
Permits hosts to inject packets into any network and have them travel independently.
Defines an official packet format and protocol (IP Internet Protocol) and a companion protocol ICMP (Internet Control Message Protocol)

Transport Layer:
Two end to end protocols:

- TCP : Transmission Control Protocol
allows a byte stream to be delivered without error. Segments the byte stream into discrete messages. On the receiving end reconstructs it into the output stream. Also handles flow control.

- UDP: User Datagram protocol
unreliable, connectionless protocol for those who want to provide their own flow control or sequencing.

Application Layer:
instead of separate session or presentation layers, apps just include whatever functions they want for these.
Contains higher level protocols like FTP, DNS, SMTP

