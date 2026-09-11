1. A layer should be created where a different abstraction is required.
2. Each layer should perform a well-defined function.
3. The function of each layer should be chosen with an eye toward defining internationally standardized protocols.

![[Pasted image 20260910151107.png]]

4. The layer boundaries should be chosen to minimize the information flow across the interfaces
5. The number of layers should be large enough so as to not ahve to throw all functions in the same layer out of necessity.

Physical Layer:
Transmits raw bits over a communication channel.

Data Link Layer:
Transforms the output of the physical layer into something that doesn't have visible transmission errors.

Breaks up the data into **Data Frames** and transmits them sequentially. If the service is reliable, the transmitter confirms the acknowledgement frames.

There might be a traffic regulation mechanism here.

In broadcast networks there is also a medium access control sublayer here that controls access to the shared channel.

Network Layer:
Handles routing based on static tables that are wired into networks. Responsible for quality of service. Handles other types of problems when packets send correctly, like protocols being different.

Transport Layer:
Accepts data from above, splits it into smaller pieces if need be. Determines what type of [[Service]] it provides to the session layer.

Session Layer:
Allows users on different machines to establish session between them. Offers services like dialog control, token management and synchronization.

Presentation Layer:
Because different computers have different internal data representations there is a need to define, translate, exchange, this layer handles that.

Application Layer:
Contains protocols the users need like HTTP.
